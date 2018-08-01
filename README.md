# Golang study repository

## Go ?
Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.
https://golang.org

## install & setting

- package install

```sh
yum install -y golang
```

- set project to go path

```sh
export GOPATH={YOUR_REPO_DIR}/golang_study
```

- check go env

```sh
# go env
GOARCH="amd64"
GOBIN=""
GOEXE=""
GOHOSTARCH="amd64"
GOHOSTOS="linux"
GOOS="linux"
GOPATH="/root/git/golang_study/"
GORACE=""
GOROOT="/usr/lib/golang"
GOTOOLDIR="/usr/lib/golang/pkg/tool/linux_amd64"
GCCGO="gccgo"
CC="gcc"
GOGCCFLAGS="-fPIC -m64 -pthread -fmessage-length=0 -fdebug-prefix-map=/tmp/go-build739687650=/tmp/go-build -gno-record-gcc-switches"
CXX="g++"
CGO_ENABLED="1"
CGO_CFLAGS="-g -O2"
CGO_CPPFLAGS=""
CGO_CXXFLAGS="-g -O2"
CGO_FFLAGS="-g -O2"
CGO_LDFLAGS="-g -O2"
PKG_CONFIG="pkg-config"
```

## Hello world! example

- edit go file

```go
package main

import "fmt"

func main() {
        fmt.Println("Hello, world!")
}
```

- build go

```sh
go build hello.go
```

- run go binary

```sh
./hello
Hello, world!
```

