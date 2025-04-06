<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-04-06T10:05:17Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2vLoryBnLM4wTr61Zclm1eokLZP",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vLoryBnLM4wTr61Zclm1eokLZP"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2vLoqYZZKFRBKZ9leNy00zcjyPX",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vLoqYZZKFRBKZ9leNy00zcjyPX"
				},
				"enabled": true
			},
			"created_at": "2025-04-06T10:05:06Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2vLoqXWcMYu02Hdn50c4sZwj1eI",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vLoqXWcMYu02Hdn50c4sZwj1eI"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
