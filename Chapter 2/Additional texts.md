### HTTP Request and Response texts

Following are a couple of actual HTTP request and response headers from FireFox web browser (Go to inspect element -> Network tab) 

```
GET /wiki/Passerine HTTP/2
Host: en.wikipedia.org
User-Agent: Mozilla/5.0 (<REDACTED>) Gecko/20100101 Firefox/139.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate, br, zstd
Referer: https://en.wikipedia.org/wiki/Russet_sparrow
Connection: keep-alive
Cookie: <REDACTED>
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: same-origin
Sec-Fetch-User: ?1
Priority: u=0, i
TE: trailers
```

```
HTTP/2 200 
date: Tue, 17 Jun 2025 04:03:09 GMT
server: ATS/9.2.9
x-content-type-options: nosniff
content-language: en
accept-ch: 
last-modified: Mon, 16 Jun 2025 02:22:51 GMT
content-type: text/html; charset=UTF-8
content-encoding: gzip
age: 25131
accept-ranges: bytes
vary: Accept-Encoding,Cookie,Authorization
x-cache: cp5018 hit, cp5018 hit/7
x-cache-status: hit-front
server-timing: cache;desc="hit-front", host;desc="cp5018"
strict-transport-security: max-age=106384710; includeSubDomains; preload
report-to: { "group": "wm_nel", "max_age": 604800, "endpoints": [{ "url": "https://intake-logging.wikimedia.org/v1/events?stream=w3c.reportingapi.network_error&schema_uri=/w3c/reportingapi/network_error/1.0.0" }] }
nel: { "report_to": "wm_nel", "max_age": 604800, "failure_fraction": 0.05, "success_fraction": 0.0}
set-cookie: WMF-DP=b91;Path=/;HttpOnly;secure;Expires=Tue, 17 Jun 2025 00:00:00 GMT
x-client-ip: <REDACTED>
cache-control: private, s-maxage=0, max-age=0, must-revalidate, no-transform
content-length: 79266
X-Firefox-Spdy: h2
```

***

### Telnet to a Website

Write the following in your terminal (one line at a time) and press enter twice to receive a response.
Note: Telnet only supports till HTTP/1.1 (and post 80 means there is no TLS).

```
telnet google.com 80
GET / HTTP/1.1
```

```
telnet google.com 80
Trying 2404:6800:4007:80f::200e...
Connected to google.com.
Escape character is '^]'.
GET / HTTP/1.1

HTTP/1.1 200 OK
Date: Thu, 19 Jun 2025 18:28:28 GMT
Expires: -1
Cache-Control: private, max-age=0
Content-Type: text/html; charset=ISO-8859-1
Content-Security-Policy-Report-Only: object-src 'none';base-uri 'self';script-src 'nonce-t6l6tmAHRJ6nH7K6E_zmtA' 'strict-dynamic' 'report-sample' 'unsafe-eval' 'unsafe-inline' https: http:;report-uri https://csp.withgoogle.com/csp/gws/other-hp
P3P: CP="This is not a P3P policy! See g.co/p3phelp for more info."
Server: gws
X-XSS-Protection: 0
X-Frame-Options: SAMEORIGIN
Set-Cookie: <REDACTED>
Set-Cookie: <REDACTED>
Accept-Ranges: none
Vary: Accept-Encoding
Transfer-Encoding: chunked
<HTML code>
```

***
