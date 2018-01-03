driebit/haproxy
===============

An image that adds a simple configuration on top of 
[haproxy:alpine](https://hub.docker.com/_/haproxy/).

To run the image, pass the `$BACKEND_SERVER` and `$BACKEND_PORT` parameters:

```bash
$ docker run -e BACKEND_SERVER="localhost" -e BACKEND_PORT=8000 driebit/haproxy
```
