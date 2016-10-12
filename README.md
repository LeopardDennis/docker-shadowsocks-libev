shadowsocks-libev
=================

## Run docker container

```bash
$ docker run --name shadowsocks -d -e METHOD=aes-256-cfb -e PASSWORD=9MLSpPmNt -p 8388:8388 --restart always leoparddennis/shadowsocks-libev
```

