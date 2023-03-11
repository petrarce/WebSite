## Running lighttpd server for testing purposes

```shell
# in current directory
DOCUMENT_ROOT=${PWD} /usr/sbin/lighttpd -D -f config
# sample static web page should be available from the http://127.0.0.1:3000
```

