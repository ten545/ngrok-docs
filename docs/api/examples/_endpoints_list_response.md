<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-21T10:05:58Z",
			"hostport": "7bd17641d5e2.ngrok.paid:443",
			"id": "ep_2qWPrkscS3uoq4RWsYKjjcyacVd",
			"name": "command_line",
			"principal": {
				"id": "usr_2qWPpGh6qvUrXbKwXBNTji1kfzV",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://7bd17641d5e2.ngrok.paid",
			"tunnel": {
				"id": "tn_2qWPrkscS3uoq4RWsYKjjcyacVd",
				"uri": "https://api.ngrok.com/tunnels/tn_2qWPrkscS3uoq4RWsYKjjcyacVd"
			},
			"tunnel_session": {
				"id": "ts_2qWPrlpSzmLyKRbvugiysfpGga9",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qWPrlpSzmLyKRbvugiysfpGga9"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-21T10:05:58Z",
			"upstream_url": "http://localhost:80",
			"url": "https://7bd17641d5e2.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-21T10:05:56Z",
			"domain": {
				"id": "rd_2qWPrHI0XJZNKvFd4irFW6LBhOx",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qWPrHI0XJZNKvFd4irFW6LBhOx"
			},
			"edge": {
				"id": "edgtls_2qWPrGfVykH1EtfJtzwy1eBwjWx",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qWPrGfVykH1EtfJtzwy1eBwjWx"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qWPrF4XPmXL1OSMy9XOyGChF3C",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-21T10:05:56Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
