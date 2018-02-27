# WULK

Simple Python3 script to set the status of Slack to working remotely
if not working from the office IP.

Not actively maintained and poor quality. 😄

## Setup

**~/.slack**
Line contains workspace name. IPs and [API token](https://api.slack.com/custom-integrations/legacy-tokens).

```
workspace-name 12.34.5.67,12.34.5.68 xoxp-....
```

**crontab**
```
*/5 * * * * ~/path/to/wulk/wulk
```

## What's in the name

- Slack
- Slak
- [Wulk](https://nl.wikipedia.org/wiki/Buccinum_undatum)
