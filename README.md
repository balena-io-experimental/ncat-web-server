Runs a simple "hello world" web server for container testing.

## Implementation

Uses the web server provided by the ncat utility. For example, to listen on port 8080:

```bash
# balena run --rm -d -p 8080:80 kb2ma/ncat-web-server
```

Then you can fetch the page from the device at the URL `http://<device-ip>:8080/index.html`.


See the section *Turn Netcat into a simple web server* on the Neat Tricks [page](https://nmap.org/ncat/guide/ncat-tricks.html) for more details.
