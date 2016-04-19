# A\* Demo (Defold) [![Build Status](https://img.shields.io/travis/unindented/defold-astar.svg)](http://travis-ci.org/unindented/defold-astar) [![Coverage Status](https://img.shields.io/coveralls/unindented/defold-astar.svg)](https://coveralls.io/r/unindented/defold-astar)

Simple A\* demo using [Defold](http://www.defold.com/).


## Setup

```
$ luarocks install luacheck
$ luarocks install busted
$ luarocks install luacov
```


## Testing

```
$ make lint test
```


## Building

### Windows

```
$ make x86-win32-build
```

### Mac OS X

```
$ make x86-darwin-build
```

### Linux

```
$ make x86-linux-build
```

### iOS

```
$ make armv7-darwin-build
```

### Android

```
$ make armv7-android-build
```

### Web

```
$ make js-web-build
```


## License

Copyright (c) 2016 Daniel Perez Alvarez ([unindented.org](https://unindented.org/)). This is free software, and may be redistributed under the terms specified in the LICENSE file.
