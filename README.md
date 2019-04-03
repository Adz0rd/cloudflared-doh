cloudflared-doh is a simple and lightweight DNS-over-HTTPS that users the latest Alpine linux as the underlying host.

Once started, the client will respond to DNS requests over port 53 and will resolve the requests against Cloudflare's 1.1.1.1 service (utilising its DOH endpoint).

The client will update itself to the latest daemon version on each container restart.
