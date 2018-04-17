# x86-who

## Quick command
`x86-who`

## Description
Copied binary of 'who' command.  List logged in users.


## Usage
### Commands
* `x86-who` - No options, just list logged in users
* `x86-who -a` or `x86-who --all` - Combines several options to add more information


### Options
* -ips - Do not resolve IPs into hostnames


## Review
Does it's job fine, but some of the options are worth exploring later.
Needs to be replaced with a statically-linked version of who.


## Location
Part of the linux-x86 tools image.


## Source
Version copied from fresh install of Ubuntu 17.10.1 Server i386
https://www.ubuntu.com/server

GNU Coreutils 8.26
http://www.gnu.org/software/coreutils/coreutils.html

