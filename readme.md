#Automatic Klipper Backup to GitHub using script

~/klipperBackup.sh

```
#!/bin/sh
git -C <location> add .
git -C <location> commit -m "`date`"
git -C <location> push origin master

<location> e.g. ~/printer_data/config
```

#Configure crontab to schedule the Script
automatedhome.party automatically backup your klipper config to github to maintain a version history

