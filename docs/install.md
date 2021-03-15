# Install

You can install the pre-compiled binary from [releases](https://github.com/helmwave/helmwave/releases),
use Docker or compile from source.

Here are the steps for each of them:

## Mac OS

> Download one of [releases](https://github.com/helmwave/helmwave/releases)

```sh
brew install helmwave/tap/helmwave
```

## Linux

> Download one of [releases](https://github.com/helmwave/helmwave/releases)

```sh
$ wget -c https://github.com/helmwave/helmwave/releases/download/0.9.1/helmwave_0.9.1_linux_amd64.tar.gz -O - | tar -xz
$ mv helmwave /usr/local/bin/
```

## Windows

> Download one of [releases](https://github.com/helmwave/helmwave/releases)


## Install with ![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/zhilyaev/helmwave)

```sh
$ GO111MODULE=on go get github.com/helmwave/helmwave/cmd/helmwave@0.9.1
```

## Compile from source

```bash
$ git clone git@github.com:helmwave/helmwave.git
$ cd helmwave
$ go build ./cmd/helmwave
$ mv helmwave /usr/local/bin/
```

