# Web Server One-liners

This is a wrapper script for launching one of the following an ad hoc http static servers to launch an instant web server on the fly.

- Python 2.x SimpleHTTPServer
- Python 3.x http.server
- Ruby WEBrick via un
- PHP (5.4+)

Default is Python 2.x or 3.x depends on your environment.

## Usage

```text
$ webserver PROGRAM PORT_NUMBER
```

### Example

```bash
# Default (Python 2.x or 3.x) using default port number
$ webserver

# Default (Python 2.x or 3.x) with an explicit port number
$ webserver 8080

# Python 2.x or 3.x
$ webserver python 8080

# Python 3.x
$ webserver python3 8080

# Ruby
$ webserver ruby 8080

# PHP
$ webserver php 8080
```

## Installation

Clone this repository (or just download the script file) to any location and add the directory to your PATH.

### Example

```text
$ cd ~
$ git clone git@github.com:5t111111/http-server-one-liner.git
$ export PATH=$HOME/http-server-one-liner/bin:$PATH
$ rehash # optional
```

Or you can install via Homebrew.

```text
$ brew tap 5t111111/web-server-one-liners
$ brew update
$ brew install web-server-one-liners
```
