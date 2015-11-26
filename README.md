linux-proxy
===
Proxy shell script for Ubuntu.

### Configure proxy:
Edit *proxy.sh* and set
* USER
* PASS
* HTTP_PROXY_HOST
* HTTP_PROXY_PORT
* HTTPS_PROXY_HOST
* HTTPS_PROXY_PORT

If not exist user and password, set empty.

### Start proxy:
```sh
./proxy start
```

### Stop proxy:
```sh
./proxy stop
```
