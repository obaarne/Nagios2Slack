# Nagios2Slack

Nagios notifications for Slack, with formatted messages :

![OK](http://env.baarnes.com/nagios2slack/ok.png)
![Critical](http://env.baarnes.com/nagios2slack/critical.png)

* Set up an incoming webhook integration in your Slack workspace.</br>
( https://my.slack.com/services/new/incoming-webhook/ )

* Copy the two scripts to your plugin directory. (location may vary)

* Edit the Slack URLs to reflect the webhooks you created in Slack.

* Define the new notification commands in Nagios.
(example in slack_commands.cfg, modify paths as required)

* Set up a new contact to use the new host and service notification commands.
