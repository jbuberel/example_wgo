# Example using `wgo` tool

* Import paths are not rewritten
* A list of GOPATHs is stored in the `.goconfig/gopaths' file
* The `wgo go build` command must be used to build the application

# To build this application:

```
$ mkdir wgo
$ cd wgo
$ export GOPATH=`pwd`
$ export GOBIN=$GOPATH/bin
$ export PATH=$GOBIN:$PATH
$ go get github.com/skelterjohn/wgo
$ go install github.com/skelterjohn/wgo
$ go get github.com/jbuberel/example_wgo
$ cd src/github.com/jbuberel/example_wgo/
$ wgo build github.com/jbuberel/example_wgo/wgoserver
```
