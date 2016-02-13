clear
=====

Clear the terminal screen if possible

Usage
-----

``` js
var clear = require('clear');
clear();
```

CLI
-----

Alternatively, you can use the `clear` cli.

``` bash
$ clear
```

Example
-------

![Node Clear](http://daveeddy.com/static/media/github/node-clear.gif)

### clear([bool])

You can optionally give clear an argument of `false` to prevent it from clearing the screen.
This will not remove anything from the screen, but instead move your cursor to
position 0,0.  Much like printing a `\r` instead of a `\n` to reset the current
line of output.

Installation
------------

    npm install [-g] clear

ANSI Codes
----------

http://www.inwap.com/pdp10/ansicode.txt

License
-------

MIT
