# Signal Webhook

## Sending Watchtower notifications using Singal API container

Watchtower's notification system doesn’t directly support Signal out of the box, we'll do a custom solution.

1. Use Watchtower's WATCHTOWER_NOTIFICATION_URL to point to a custom webhook:
    - Instead of sending the notification to a service like Slack or Discord, you can point it to a custom webhook that will relay the notification to your Signal API container.

2. Create a custom webhook service:
    - You can write a small service (e.g., in Python or Node.js) that will act as a middleman.
      This service would:
        - Receive the Watchtower notification.
        - Parse the notification payload.
        - Send the parsed message to your Signal API container.

## Test with curl

```sh
curl -X POST http://localhost:5000/webhook \
-H "Content-Type: application/json" \
-d '{
  "Entries": [
    {"Message": "Test message 1"},
    {"Message": "Test message 2"}
  ]
}'
```
