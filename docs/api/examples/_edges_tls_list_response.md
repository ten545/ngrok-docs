<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-21T10:06:06Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qWPskRj37Jw4G26fPIVyxZePR1",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qWPskRj37Jw4G26fPIVyxZePR1"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qWPrCMprx4kEIeQPALCAxorwG6",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qWPrCMprx4kEIeQPALCAxorwG6"
				},
				"enabled": true
			},
			"created_at": "2024-12-21T10:05:54Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qWPrGfVykH1EtfJtzwy1eBwjWx",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qWPrGfVykH1EtfJtzwy1eBwjWx"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
