README.md

signal-worldle-scoreboard bot

This bash script acts as a signal group chat bot that publishes information about group members' individual Worldle scores of the day to a scoreboard hosted on Keep the Score. The script runs several times a day (with a cron job) looking for new messages on signal-cli with people's Worldle scores from a given group. It then parses the scores into something that can be communicated to the KeepTheScore API in the background.

Requirements:
- Having signal-cli installed with a phone deviced linked or registered.

Setup:
