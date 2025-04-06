<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-04-06T10:05:12Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2vLoqYNcpRQ0RellQymLk6vPcLh",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2vLoqYNcpRQ0RellQymLk6vPcLh"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2vLorKfUXmRJVJLLFUSAjsgYnvz",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-04-06T10:05:12Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2vLorKfUXmRJVJLLFUSAjsgYnvz",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-06T10:05:09Z",
			"hostport": "d3d1aa7035c8.ngrok.paid:443",
			"id": "ep_2vLor1oi2QKycP0yTY4R31lOuk6",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2vLoodgykiRXAYvpbKhItO7P61p",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://d3d1aa7035c8.ngrok.paid",
			"tunnel": {
				"id": "tn_2vLor1oi2QKycP0yTY4R31lOuk6",
				"uri": "https://api.ngrok.com/tunnels/tn_2vLor1oi2QKycP0yTY4R31lOuk6"
			},
			"tunnel_session": {
				"id": "ts_2vLoqxzRfmh5VIaLL2BIxUE8Kwn",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2vLoqxzRfmh5VIaLL2BIxUE8Kwn"
			},
			"type": "ephemeral",
			"updated_at": "2025-04-06T10:05:09Z",
			"upstream_url": "http://localhost:80",
			"url": "https://d3d1aa7035c8.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-06T10:05:07Z",
			"domain": {
				"id": "rd_2vLoqYNcpRQ0RellQymLk6vPcLh",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2vLoqYNcpRQ0RellQymLk6vPcLh"
			},
			"edge": {
				"id": "edgtls_2vLoqXWcMYu02Hdn50c4sZwj1eI",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2vLoqXWcMYu02Hdn50c4sZwj1eI"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2vLoqWsFaXbwBQfKIQCEhbdoRnR",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-04-06T10:05:07Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
