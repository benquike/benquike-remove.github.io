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
## security
* openssl

## Graphics
* libgtk

## Developing
* cpputest
* test coverage analysis

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
cpputest lcov genhtml
gnuplot
expect
tilda guake terminator
valgrind
nasm
boost
astyle
r2
execstack
pandas
```


# Reference
## Important tools
1. [Automation with Expect Scripts](http://www.admin-magazine.com/Articles/Automating-with-Expect-Scripts)

## terminal emulators
1. [Tilda](https://github.com/lanoxx/tilda)

## Program analysis
1. [Using Valgrind to Find Memory Leaks and Invalid Memory Use](http://www.cprogramming.com/debugging/valgrind.html)
2. [Using Valgrind](http://web.cs.swarthmore.edu/~newhall/unixhelp/purify.html)
3. [Valgrind](http://pages.cs.wisc.edu/~bart/537/valgrind.html)
4. [Valgrind tool explained](http://cs.ecs.baylor.edu/~donahoo/tools/valgrind/)

## Privacy and security related
1. [PGP](http://cs.ecs.baylor.edu/~donahoo/tools/PGP/)

## source code formatter
1. [Artistic Style](http://astyle.sourceforge.net/astyle.html#_General_Information)
