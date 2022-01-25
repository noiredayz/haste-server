This is a continued version of hastebin server.

Originally continued by [zneix](https://github.com/zneix) with extended development, currently maintained by me btw.

**This version is heavily changed, meaning there will be breaking changes in your config if you were running outdated upstream version.**

# Haste

Haste is an [free software](https://www.gnu.org/philosophy/free-sw.en.html) pastebin-like software written in Node.JS, which is easily installable in any network.  
It can be backed by either redis or filesystem and has a very easy adapter interface for other storage systems.  

Major design objectives:

* Be really pretty
* Be really simple
* Be easy to set up and use

Check out the command line client [haste-client](https://github.com/zneix/haste-client), which can do things like:

`cat file | haste`

it outputs URL to a paste containing contents of `file`. Check [repo](https://github.com/zneix/haste-client) for more details.


# Installation

Full installation and config instructions can be found in **docs** directory


## Authors

This fork is maintained by noiredayz.

Project continued by zneix <zzneix@gmail.com>

Original Code by John Crepezzi <john.crepezzi@gmail.com>


## Other components:

* jQuery: MIT/GPL license
* highlight.js: Copyright © 2006, Ivan Sagalaev
* highlightjs-coffeescript: WTFPL - Copyright © 2011, Dmytrii Nagirniak
