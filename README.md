# Example using `wgo` tool

* Import paths are not rewritten
* A list of GOPATHs is stored in the `.goconfig/gopaths' file
* The `wgo go build` command must be used to build the application

# To build this application:

```
$ go get github.com/skelterjohn/wgo
$ go get github.com/skelterjohn/vendor
$ git clone https://github.com/jbuberel/example_wgo
$ cd example_wgo
$ wgo restore
$ wgo install wgoserver
```
