Installing tools
================

This guide is optional and assumes macOS. If you have a preferred
different way of doing it, feel free to.

Pre-requisites
--------------

-   [Homebrew](https://brew.sh/) installed
-   [asdf](https://asdf-vm.com/guide/getting-started.html) installed
-   GNU Bash or Zsh

HOWTO
-----

    cd /path/to/this/repository
    asdf plugin add golang
    asdf install

Optionally afterwards, from the same folder:

    go install golang.org/x/tools/gopls@latest
    go install golang.org/x/tools/cmd/goimports@latest

Editor setup
------------

-   [Visual Studio
    Code](https://github.com/golang/vscode-go/blob/master/README.md)
-   [Emacs](https://github.com/dominikh/go-mode.el), plus
    [eglot](https://joaotavora.github.io/eglot/)
