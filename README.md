log4go
======

Simplified Logging API for go

== Installation ==

We support installation via the go tool which can be invoked using the following command-line:

    go get github.com/hugozhu/log4go

== Usage ==
```
    import (
        "github.com/hugozhu/log4go"
    )

    var log = log4go.New(os.Stdout)

    func main() {
        log.Debug("Hello, World!")
    }
```    