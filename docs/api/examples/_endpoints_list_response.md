<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-10T15:25:13Z",
			"hostport": "36c450768c3d.ngrok.paid:443",
			"id": "ep_2q1yKe0qYlBMnm5IA4qzqyffveI",
			"name": "command_line",
			"principal": {
				"id": "usr_2q1yICe4NZlw3J0kVSEJKl7adPz",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://36c450768c3d.ngrok.paid",
			"tunnel": {
				"id": "tn_2q1yKe0qYlBMnm5IA4qzqyffveI",
				"uri": "https://api.ngrok.com/tunnels/tn_2q1yKe0qYlBMnm5IA4qzqyffveI"
			},
			"tunnel_session": {
				"id": "ts_2q1yKim6ichNM3B8QqY6QWm0eMm",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2q1yKim6ichNM3B8QqY6QWm0eMm"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-10T15:25:13Z",
			"upstream_url": "http://localhost:80",
			"url": "https://36c450768c3d.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-10T15:25:10Z",
			"domain": {
				"id": "rd_2q1yKCHZ9xdSqupdecPR77JGZul",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2q1yKCHZ9xdSqupdecPR77JGZul"
			},
			"edge": {
				"id": "edgtls_2q1yKBkh1pSGBg8rkQ8nlwP1KDw",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2q1yKBkh1pSGBg8rkQ8nlwP1KDw"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2q1yKDfcF0HrhZ5nE5bAjGdOkSo",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-10T15:25:10Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
