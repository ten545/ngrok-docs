<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-12-21T10:06:02Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2qWPsDRxz7BKBbJPDmthcuVQmgT",
					"uri": "https://api.ngrok.com/event_destinations/ed_2qWPsDRxz7BKBbJPDmthcuVQmgT"
				}
			],
			"id": "esb_2qWPsCVVKwlNuSR5uESUZNt6N2H",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2qWPsCVVKwlNuSR5uESUZNt6N2H/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2qWPsCVVKwlNuSR5uESUZNt6N2H"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
