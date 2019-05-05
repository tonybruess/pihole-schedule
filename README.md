# pihole-schedule

Schedule pi-hole blocks for Instagram, Twitter, Slack, etc

## Usage

1. Clone the repo into `/etc`
2. Customize `pihole-schedule.cron`
3. Link the binaries
4. Install the crontab
5. You're done! :party:

```
git clone git@github.com:tonybruess/pihole-schedule.git /etc
vim pi-hole.cron
ln -s /etc/pihole-schedule/bin/* /usr/local/bin
crontab /etc/pihole-schedule/pihole-schedule.cron.cron
```
