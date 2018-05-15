# About

Docker containers for [fatedier/frp](https://github.com/fatedier/frp).

## Usage of frps

- Get help

```console
$ docker run --rm lonwern/frps --help
```

- Start server

```console
$ docker run -d --name some-fprs \
    -v /some/conf:/conf \
    lonwern/frps -c /conf/frps.ini
```

## Usage of frpc

- Get help

```console
$ docker run --rm lonwern/frpc --help
```

- Start client

```console
$ docker run -d --name some-fprc \
    -v /some/conf:/conf \
    lonwern/frpc -c /conf/frpc.ini
```