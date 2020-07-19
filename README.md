# Transfer

Snippet Transfer Tools

### Installation

`./install.sh`

Git Bash on Windows doesn't have `make`.

### Usage

* `transfer | foo` is output and default
* `foo | transfer -` is input mode

The concept is that if you give it a file, it takes input from that,
otherwise it provides output.

### Helpers

* [`cb`](README_CB.md), for transferring to and from the clipboard

### Future Changes

* Support for files, not just `stdin` (`-`)
