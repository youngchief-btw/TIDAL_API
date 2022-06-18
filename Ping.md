# Ping TIDAL Server

`GET https://listen.tidal.com/v1/ping`

This endpoint seems to return a `HTTP 200 OK` under the right request headers. I believe it has to be `Referrer`, `Cookie`, `Accept`, and/or `Accept-Encoding`. Otherwise returns the web app page saying it couldn't find that page.
