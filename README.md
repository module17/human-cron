# human-cron

A simple bash script that presents crontab entries in human readable format.

The script uses the `crontab` command avaliable in most Linux distributions.

### Sample use:
```bash
./human-cron.sh [user]
```

### Sample output:
```
-+ Command /usr/sbin/quotacheck -avug  will be executed everyday at hour 3:00
```

The output is available in both Polish and English language. 
The `master` branch is Polish; English is available in the `english` branch.

Version 1.1
