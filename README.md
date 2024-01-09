# Disk-Health
# SAS disk
## SMART values
sch: https://www.google.com/search?q=hpsa+driver+smart+disk+health

### Guide:
https://phuoctaihuynh.wordpress.com/2017/12/08/hp-server-disk-health-check/ [ark:](https://web.archive.org/web/20240109131421/https://phuoctaihuynh.wordpress.com/2017/12/08/hp-server-disk-health-check/)

>To look at disks behind HP Smart Array controllers, use syntax such as:
>```
>smartctl -a -d cciss,0 /dev/cciss/c0d0 (cciss driver under Linux)
>smartctl -a -d cciss,0 /dev/sg2 (hpsa or hpahcisr drivers under Linux)
>```
