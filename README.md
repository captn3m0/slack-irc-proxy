# slack-irc-proxy

** THIS REPO WAS JUST AN IDEA. See <https://github.com/ekmartin/slack-irc> for a real implementation **

Do you have a slack team and most of your team hangs out on an IRC channel as well?

Well, slack-irc-proxy allows you to:

- create multiple IRC-synced channels
- Let your team authenticate to IRC with their own credentials
- talk to an IRC channel on freenode via slack

# Why is this useful?

We at @SDSLabs often hold contests and participate in others. We often need to be online
on IRC for such events (such as #backdoorctf). Since most of us are already online on
Slack anyway and Slack has such an awesome developer API, I thought it would be cool
to create a proxy that allows us to talk in an IRC channel without having to use another
IRC client.

Also, the mobile experience of Slack is far better than most mobile IRC clients.

If you are an open organization with an open IRC channel that you monitor and a closed slack team,
you might wanna set this up.

# Deployment

This app is ready to be deployed on Heroku with the Heroku button.

# Configuration

You can add or remove irc channels via editing the config.
