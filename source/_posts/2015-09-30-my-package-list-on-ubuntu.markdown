---
layout: post
title: "My Package List on Ubuntu"
date: 2015-09-30 17:46:06 -0400
comments: true
categories: 
---

# editors
* emacs
* vim
* kate
* sublime-text

# libraries
* openssl
* libgtk

# typesetting
* texlive
* texstudio

# text tool
* dos2unix

# Shell and terminal
* zshell
* tmux

# Installing them in one line of command

```bash
$ sudo add-apt-repository -y ppa:webupd8team/sublime-text-3
$ sudo apt-get install build-essential build-dep #
vim emacs lv kate sublime-text-installer # editors
gnupg2 openssh-client openssh-server libssl0.9.8
texlive-full texstudio
git tig ipython
bbdb3 curl zip rar markdown
indent dos2unix
zlib-gst zlib1g-dev libgtk2.0-dev libfdt-dev libcurl4-gnutls-dev
zsh tmux
w3m jekyll python 
shutter
dia graphviz
llvm clang
cmake automake
```
