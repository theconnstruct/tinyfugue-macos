# tinyfugue-macos

This has been patched specifically for macOS.

## Requirements

Install `openssl` and `pcre` via Homebrew.

## Build Instructions

1. Clone this repo and `cd` into it.
2. Run `./configure --enable-getaddrinfo --with-ssl --with-inclibpfx="/opt/homebrew/opt/openssl /opt/homebrew/opt/pcre"`
3. Run `make install clean`.

The binary will be placed by default at `$HOME/bin/tf`.