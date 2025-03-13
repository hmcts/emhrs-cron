# EMHRS Cron Helm Chart

Helm chart for the EMHRS kubernetes cron job. It uses the [em-hrs-api](https://github.com/hmcts/em-hrs-api) image to execute scheduled tasks by passing the arguments: `run [taskname]` to the jar.
