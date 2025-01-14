# squid
Squid is a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more.

## Now apply template to container
```sh
bastille create squid 14.1-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/squid; bastille template squid bastille-templates/squid
```