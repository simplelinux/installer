```` bash
(pv -n /dev/sda | dd of=/dev/sdb bs=128M conv=notrunc,noerror) 2>&1 | dialog --gauge "Running dd command (cloning), please wait..." 10 70 0
````

Preview:
http://www.cyberciti.biz/faq/linux-unix-dd-command-show-progress-while-coping/
