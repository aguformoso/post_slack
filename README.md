# post_slack
Simple BASH script for POSTing to the Slack API with custom messages.

## Usage
```
env SLACK_URL=<your_slack_url> ./post_slack --title "<message_title>" --body "<message_body>"
```

### Command line params (mandatory)
*-t | --title*: Message title.
*-b | --body*: Message body.
*-c | --color*: Message color. Color options are: good warning danger error.
*-u | --url*: Slack URL to send the POST. Overrides env SLACK_URL variable.
*-h | --help*: Print a help message.
