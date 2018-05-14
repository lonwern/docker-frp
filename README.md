# About

Docker containers for [fatedier/frp](https://github.com/fatedier/frp).

## Usage of frps

- get help

```console
$ docker run --rm lonwern/frps --help
```

- start

```console
$ docker run -d --name some-fprs \
    -v /some/conf:/conf \
    lonwern/frps -c /conf/frps.ini
```

## Usage of frpc

- get help

```console
$ docker run --rm lonwern/frpc --help
```

- start

```console
$ docker run -d --name some-fprc \
    -v /some/conf:/conf \
    lonwern/frpc -c /conf/frpc.ini
```