# puppet-slack_webhook

Puppet module for sending monit notifications to Slack

# Usage - triggers slack alerts for monit

You can call the class like this:

    class { '::slack_webhook':
        key => 'your-slack-key',
    }

where 'your-slack-key' is the string of jibberish in the Slack Webhook URL.

Alter the monit fragment as needed for your nodes.
