Laptop
======

Laptop is a script to set up your Max OS X laptop as a commercetools development machine.

Requirements
------------

* A C compiler, such as GCC, LLVM, or Clang.

Download a compiler from [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) if you're on Snow Leopard (OS X 10.6) or [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action) if you're on Lion (OS X 10.7).

* bash as your login shell.

To change your login shell run this from a Terminal:

    chsh -s /bin/bash

Install
-------

Run the script:

    bash < <(curl -s https://raw.github.com/svenmueller/laptop/master/mac)

What it sets up
---------------

* SSH public key (for authenticating with services like Github and Heroku)
* Homebrew (for managing operating system libraries)
* Git (for managing versions of code)
* curl and wget (for executing HTTP requests)
* Ack (for finding things in files)
* htop (for displaying running processes)


It should take about a couple of minutes for everything to install, depending on your machine.
