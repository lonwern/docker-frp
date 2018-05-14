# About

Docker containers for [fatedier/frp](https://github.com/fatedier/frp).

## Usages of frps

```console
$ docker run --rm lonwern/frps --help
```

```console
$ docker run -d --name some-fprs \
    -v /some/conf:/conf \
    lonwern/frps -c /conf/frps.ini
```

## Usages of frpc

```console
$ docker run --rm lonwern/frpc --help
```

```console
$ docker run -d --name some-fprc \
    -v /some/conf:/conf \
    lonwern/frpc -c /conf/frpc.ini
```