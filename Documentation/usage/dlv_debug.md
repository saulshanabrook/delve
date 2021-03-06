## dlv debug

Compile and begin debugging main package in current directory, or the package specified.

### Synopsis


Compiles your program with optimizations disabled, starts and attaches to it.

By default, with no arguments, Delve will compile the 'main' package in the
current directory, and begin to debug it. Alternatively you can specify a
package name and Delve will compile that package instead, and begin a new debug
session.

```
dlv debug [package]
```

### Options inherited from parent commands

```
      --accept-multiclient[=false]: Allows a headless server to accept multiple client connections. Note that the server API is not reentrant and clients will have to coordinate.
      --api-version=1: Selects API version when headless.
      --build-flags="": Build flags, to be passed to the compiler.
      --headless[=false]: Run debug server only, in headless mode.
      --init="": Init file, executed by the terminal client.
  -l, --listen="localhost:0": Debugging server listen address.
      --log[=false]: Enable debugging server logging.
      --wd=".": Working directory for running the program.
```

### SEE ALSO
* [dlv](dlv.md)	 - Delve is a debugger for the Go programming language.

###### Auto generated by spf13/cobra on 15-Feb-2017
