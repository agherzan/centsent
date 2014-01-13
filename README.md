##Table of Contents##
- [A. Description](#a-description)
- [B. Installation](#b-installation)
    - [B.1. Prerequisites](#b1-prerequisites)
    - [B.2. Install](#b2-install)
- [C. Configuration](#c-configuration)


A. Description
==============
centsent is a script to be used in conjuction with centerim5 to notify desktop
about new chat entries. The notifications will come ONLY if the focused window
is not the one running centerim5. It uses libnotify


B. Installation
===============

B.1. Prerequisites
------------------
It uses libnotify so make sure you have installed 'notify-send'.

You should have centerim5 installed on your system. For more info check:
http://www.centerim.org/index.php/Main_Page

After compiling and installing centerim, install needed plugin:
    $ cd <centerim source directory>
    $ cp plugins/.libs/extaction.so ~/.centerim5/plugins

B.2. Install
------------
Just copy centsent wherever you want but remember the path.


C. Configuration
================
Run centerim, go to Setting/Plugins, activate "External actions" and set
"Command:" to point to the file you copied in 'B.2. Install'.
