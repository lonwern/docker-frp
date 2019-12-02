# About

Docker images for [fatedier/frp](https://github.com/fatedier/frp).

## Usage of frps

- Get help

```console
$ docker run --rm lonwern/frps --help
```

- Start server

```console
$ docker run -d --name some-fprs \
    -v /path/to/frps.ini:/frps/frps.ini \
    lonwern/frps -c /frps/frps.ini
```

## Usage of frpc

- Get help

```console
$ docker run --rm lonwern/frpc --help
```

- Start client

```console
$ docker run -d --name some-fprc \
    -v /path/to/fprc.ini:/fprc/fprc.ini \
    lonwern/fprc -c /fprc/fprc.ini
```