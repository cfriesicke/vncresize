# vncresize

A command-line tool to resize the server's screen inside a running VNC session.

Example usage: `vncresize 2400x800`


## Dependencies

* Python 3.6
* xrandr (command-line binary should be installed and in your `$PATH`)

The dependency on Python 3.6 is mainly due to the convenient use of format
f-strings. However, the code is not complex; if necessary, it should be
possible to support lower Python versions as well.


## Installation

* Clone the Git repository, and move `vncresize` to a directory in your `$PATH`
* Ensure that it is executable: `chmod 755 vncresize`

