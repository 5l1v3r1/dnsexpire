# dnsexpire
PHP tool to test alias domain expiration date of a given domain list  
Note that this is an automated tool, manual check is still required.  

```
Usage: php dnsexpire.php [OPTIONS] -d <domain>

Options:
	-a	set alert for result output, default=30 days
	-d	set domain
	-f	input file
	-h	print this help

Examples:
	php dnsexpire.php -d example.com
	php dnsexpire.php -a 10 -f dns.txt -d example.com
```

I don't believe in license.  
You can do want you want with this program.  

