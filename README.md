# centos-scripts

## chksec
Looks in /var/log/secure for login failures.

Usage:
  grep for string:    /root/sbin/chksec -g <string>
  reset:              /root/sbin/chksec -r



## setbanner
Selects the banner file that will displayed in the MOTD.

Usage:
    /root/sbin/setbanner <banner-name>       (without .banner extention)
    /root/sbin/setbanner -l                  prints a list of existing banners



## systemstats
prints a list of system statistics, such as hostname, OS, load average, available memory, etc.


## updatemotd
Uses the selected banner and systemstats to populate /etc/motd.
