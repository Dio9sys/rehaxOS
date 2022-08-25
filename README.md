# rehaxOS
RehaxOS - a pentesting VM based on ReactOS

![screenshot](https://raw.githubusercontent.com/Dio9sys/rehaxOS/main/Screenshot%20from%202022-08-25%2013-49-28.png)

## What is RehaxOS?
RehaxOS is a red team 32 bit virtual machine based on ReactOS 0.4.14.

It is a virtualbox image of a base installation of ReactOS and then a number of tools added overtop and a background added.

## Did you do anything significant to the internal workings of the OS?
No.  This is simply a warm VM image.

## Why did you do this?
I have two main reasons why I did this:

1. I wanted to see if ReactOS is stable enough to serve a useful purpose, in this case penetration testing
2. I thought it would be funny

## Features list
As an offensive security product, RehaxOS has a number of features.  Try them out!

1. Surf the internet (firefox, otter, D+)
2. Edit files (notepad++, HexEd)
3. Run some of your favorite utilities (GNU utils for cmd)
4. Run penetration tests! (PentestBox suite of software, metasploit)
5. Write code (python 3)

### A note on stability
There are many programs which either crash immediately or exhibit strange behavior.  For example, PentestBox is built mostly on ConEmu.  ConEmu can't seem to open a console, and you also can't close the program either without restarting the VM.  Use this at your own risk.  I cannot stress enough that this is mostly a joke and a stress test for ReactOS

### Installation
This file is an OVA file.  You should be able to open it in Virtualbox or VMWare and it will set up the machine right away.  The RAM is set to 2 GB, but you can try upgrading that if you wish.  Please be aware that, as a 32-bit operating system, this VM has limits on how much RAM it can access.

### License
This project is based on ReactOS, which is licensed under ther GNU Public License v.3
