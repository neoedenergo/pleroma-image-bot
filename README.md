## If you are on GitHub this is a mirror, the original repository with the latest updates is at [https://forgejo.neoeden.org/ergo/pleroma-image-bot](https://forgejo.neoeden.org/ergo/pleroma-image-bot
)
---

Posts images from a directory to a fediverse account, to be triggered by a cronjob.

Cronjob example:

```
*/30 * * * * /usr/bin/python3 /home/myuser/files/bots/supercoolbot/supercoolbot.py >> /home/myuser/files/bots/supercoolbot/supercoolbot_cron.log 2>&1
```

This will execute it every 30 mins and save the logs to the specified file
