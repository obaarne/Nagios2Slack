# Nagios2Slack

Nagios notifications for Slack, with formatted messages :

![OK](http://env.baarnes.com/nagios2slack/ok.png?git)
![Critical](http://env.baarnes.com/nagios2slack/critical.png?git)

* Set up an incoming webhook integration in your Slack workspace.</br>
( [https://my.slack.com/services/new/incoming-webhook/](https://my.slack.com/services/new/incoming-webhook/) )

* Copy the two scripts to your nagios plugins directory. ( could be '/usr/lib64/nagios/plugins/' but location may vary )

* Edit the Slack URLs in both scripts to reflect the webhooks you created in Slack.

* Edit yout nagios host full qualified domain name on both scripts.

* Define the new notification commands in Nagios.
( see examples in slack_commands.cfg, modify any paths as required)

* Set up a new contact to use the new host and service notification commands.
