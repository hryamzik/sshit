# sshit

Lost direct ssh access to your servers due to new security policies and have to log in with [centrify](https://www.centrify.com/) using browser? Miss `+c` and `+v` shortcuts in that browser ssh session? Sshit!

This tool has some issues and code is a bit dirty, it's more a proof of concept than a production ready software.

## usage

`sshit` expects that 2f auth is enabled. It will store your username in `~/.centrify/sshit.yml`, password in keychain and could even store 2f token in keychain if you put `qr.gif` to a working directory.
Run with no arguments to get list of hosts available over ssh, use host name as a single argument to connect.
