# vncresize

A command-line tool to resize the server's screen from inside a VNC session.

Usage:
    ```vncresize 2400x800```


## Dependencies

* Python 3.6
* xrandr (command-line binary should be installed on your system)

The dependency on Python 3.6 is mainly due to the convenient use of format
f-strings. The code is not complex; if necessary, it should be possible to
support lower Python versions as well.

