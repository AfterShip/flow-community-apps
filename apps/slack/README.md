# Usage 

### Incoming webhook path

In your Slack app settings, you can find `Incoming Webhooks` page, your webhook looks like `https://hooks.slack.com/services/xx/xxx/xxxx`.

This `incoming_webhook` only need the path `/services/xx/xxx/xxxx`.

### Text
Plain text message send to Slack, required, accept `String`

If a blocks provided, Slack will send blocks message prioritized, else will send text as the message.

### Blocks

Blocks is a JSON array, used for formatted message. You can build and preview Slack block here [https://app.slack.com/block-kit-builder/](https://app.slack.com/block-kit-builder/)


# Reference

You can always find more information in [Slack developer center](https://api.slack.com/messaging/webhooks).
