# Mirrorscript
Script to change Kali repository mirror

http://http.kali.org redirects you to the closest available mirror based on your physical location.
Most of the time the servers may experience heavy load slowing down upgrades even with fast connection.
This script lets you rank(based on the server's ping) and choose an alternative mirror and override it.

The script works on a threaded model now, making ranking extremely quick.

You can find the original mirror list here http://http.kali.org/README.mirrorlist

# Requirements
Kali Linux

Python2.7

# Usage

```python2.7 mirrorscript.py```
