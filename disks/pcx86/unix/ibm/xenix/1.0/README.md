---
layout: page
title: IBM PC XENIX 1.0
permalink: /disks/pcx86/unix/ibm/xenix/1.0/
machines:
  - id: ibm5170
    type: pcx86
    debugger: true
    config: /devices/pcx86/machine/5170/cga/640kb/rev3/debugger/machine.xml
    autoMount:
      A:
        name: IBM XENIX 1.0 (BOOT)
      B:
        name: None
    autoStart: true
---

IBM PC XENIX 1.0
----------------

{% include machine.html id="ibm5170" %}

From [OS/2 Museum](http://www.os2museum.com/wp/ibm-pc-xenix/):

> The IBM PC XENIX was based on AT&amp;T’s UNIX System III (rather than the newer System V) with a number of BSD
enhancements. The latter included vi, C shell, and termcap/curses. Microsoft also implemented several enhancements,
such as the ability to read and write DOS file systems.

> Much like other Xenix variants before and after, IBM PC XENIX was optionally shipped with Text Formatting System
(TFS) and Software Development System (SDS) packages. The TFS was based on the classic nroff/troff formatters and
associated utilities. The SDS included a compiler, assembler, debugger, and assorted development tools like SCCS and
make.

> One of the Microsoft-specific enhancements was the ability to cross-compile to DOS using the SDS. The XENIX to DOS
cross-development capability was likely frequently used internally at Microsoft in the mid-1980s.

> The IBM PC XENIX came with rudimentary networking capabilities, namely uucp and micnet, though little is known about
their specifications.

![IBM PC XENIX 1.0 Extensions Disk 1]({{ site.pcjs-disks.baseurl }}/pcjs-disks/pcx86/unix/ibm/xenix/1.0/IBM-XENIX-100-EXT1.jpg)

![IBM PC XENIX 1.0 Extensions Disk 2]({{ site.pcjs-disks.baseurl }}/pcjs-disks/pcx86/unix/ibm/xenix/1.0/IBM-XENIX-100-EXT2.jpg)
