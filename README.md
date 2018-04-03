```
glFTPd v2.09 ():
Fix:	Installer script on FreeBSD >= 10.
Change:	The -I flag now takes an argument specifying the timeout in seconds.
Fix:	Segfault when missing last arg for a stat_section in combination with the %IX cookie.
Change:	Last argument for stat_section is now optional and defaults to "no".
	Other stat_section lines with missing first or second arg are now completely ignored.
Fix:	Libcopy for FreeBSD >= 10.
Fix:	PASV and other things on FreeBSD.
Fix:	Support for both IPv6 and IPv4 on MacOS via the installer script (thanks to bonified2x for reporting and testing)
Change: Changed secure_ip to disable hostnames in the default glftpd.conf template file.
Change: Uncommented the secure_ip setting in the default glftpd.conf template file.
```