# fail2slack
Posts fail2ban logs to Slack!

* Create a webhook for your Slack account
* Replace the `URL` config var with your Slack hook URL
* Replace the `SENDTO` config var with a Slack `@username` or `channel` to receive the messages
* Make sure the `LOGPATH` config var is point to your fail2ban logs
* Defaults to bans from today (change the `DATE` and `LOGPATH` to read past dates)
* Make sure the script has permissions to read the logs

You can now run the script manually or set up a cron to periodically send you reports while you Slack hard.

Made in collaboration with the beautiful [Nubzzz](https://github.com/nubzzz).
