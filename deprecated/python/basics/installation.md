title: Installing Python
description: Learn how to install Python 3 on your machine

# Installation

Learn how to install Python 3 on your machine.

But, before actually installing there are some points that I would like you to note. Python actually comes pre-installed on most operating system these days, but its the old and legacy version Python 2.

Python 2 will officially be retiring on Jan 1st, 2020, so its ideal to straight away get working with Python 3. Check out the installation instructions as per your operating system.

## Installing on Windows

Installing Python 3 on Windows is just as easy as installing any other program, in addition to Python 3, I would highly recommend installing **Git Bash**, so that you can work with the exact same commands in the tutorial as mine and we need not keeping on switching between operating systems. Ofcouse, I will let you know whenever there are differences.

Navigate to following link and download the setup file

    https://www.python.org/downloads/windows/

Under {==Stable Releases==} check out your system and download the setup file accordingly, in most cases your system should be 64 bit, if that's the case you can download the following setup file

    Windows x86-64 executable installer

After downloading you can install it as you would install any other program. The installer will install everything and also setup environment variables.

## Installing on Mac

Navigate to following link and download the setup file

    https://www.python.org/downloads/mac-osx/

Under {==Stable Releases==} you can download the following file

    macOS 64-bit installer

And then install it as any other program, it will automatically setup environment variables for you.

**Alternatively**

If you are using brew, then installing Python is very simple, open your terminal and type

    brew install python

By default brew will install python 3 to the following directory -

    /usr/local/bin/python3

You can check it by typing the following on your terminal

    which python3

## Installing on Linux

Installing Python 3.7 on Ubuntu.

If you are using Ubuntu 19.04 Disco Dingo then you already have Python 3.7.3 pre-installed, just sit back and you can directly skip to "Setting Up Alias"

For others, start by updating ubuntu, open your terminal and type the following -

    sudo apt update
    sudo apt install software-properties-common

Add the repository

    sudo add-apt-repository ppa:deadsnakes/ppa

Install Python 3.7

    sudo apt install python3.7

## Checking Version

You can check the installed python version.

    python3 --version

Python 3 also installs "pip3" by default, it is the package manager for python, you can check its version by

    pip3 --version

## Setting Up Alias (Optional)

Since Python 2 comes pre-installed on almost all the operating systems, the default {==python==} keyword points to Python 2, for using Python 3 we need to type {==python3==}, which for me gets a little boring and unintuitive since Python 2 will be reaching its end of life soon.

So, I just setup a alias, which simply means that, I say to my computer, "Whenever I type {==python==} it has to refer to Python 3 and not to Python 2".

To setup a alias open your terminal and navigate to your home directory

    cd

If you are using bash, open the bash_profile, since I am using Visual Studio Code, I can directly open the file by typing

    code .bash_profile

If you are using atom, you can open by

    atom .bash_profile

Or if you are using PyCharm

    charm .bash_profile

Instead of bash if you are using zsh, you can open .zshrc

    code .zshrc

Add the following 2 lines at the end of the file

    alias python='python3'
    alias pip='pip3'

Now close and restart your terminal, to check if its working properly type the following

    python --version

It should show the current Python 3 installed version.

## Setting up your development environment and code editor

(External Links)

Excellent environment setup videos by Corey Schafer -

[For Windows](https://www.youtube.com/watch?v=-nh9rCzPJ20)

[For MacOS](https://www.youtube.com/watch?v=06I63_p-2A4)

## Please Consider a Donation ❤️

All the work is provided free of cost and completely open source, but it needs your support and love to keep the activity sustainable.

Any support is genuinely appreciated, you can help by sending a small donation by clicking the below link:

[<img src="../../../images/paypal-logo.png" alt="Paypal" title="Paypal" width="200"/>](https://www.paypal.me/octallium)
