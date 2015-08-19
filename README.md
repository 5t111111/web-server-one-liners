# HTTP Server One-liner

This is a wrapper script for the following http servers to launch an instant web server on the fly.

- Python 2.x SimpleHTTPServer
- Python 3.x http.server
- Ruby WEBrick via un
- PHP (5.4+)

Default is Python 2.x or 3.x depends on your environment.

## Usage

```text
$ httpserver PROGRAM PORT_NUMBER
```

### Example

```bash
# Default (Python 2.x or 3.x) using default port number
$ httpserver

# Default (Python 2.x or 3.x) with an explicit port number
$ httpserver 8080

# Python 2.x or 3.x
$ httpserver python 8080

# Python 2.x
$ httpserver python2 8080

# Python 3.x
$ httpserver python3 8080

# Ruby
$ httpserver ruby 8080

# PHP
$ httpserver php 8080
```

## Installation

Clone this repository (or just download the script file) to any location and add the directory to your PATH.

### Example

```text
$ cd ~
$ git clone git@github.com:5t111111/http-server-one-liner.git
$ export PATH=$HOME/http-server-one-liner:$PATH
$ rehash # optional
```
