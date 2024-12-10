<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-10T15:25:21Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2q1yLgfP6g1JW1C96KsWGbJ1yqn",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2q1yLgfP6g1JW1C96KsWGbJ1yqn"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2q1yKA1s8kLNzfh5YemwC5rJAwC",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2q1yKA1s8kLNzfh5YemwC5rJAwC"
				},
				"enabled": true
			},
			"created_at": "2024-12-10T15:25:09Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2q1yKBkh1pSGBg8rkQ8nlwP1KDw",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2q1yKBkh1pSGBg8rkQ8nlwP1KDw"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
