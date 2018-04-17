# x86-lsof

## Quick command
`x86-lsof -n`
Running executables with their ports, connections, and files. Do not resolve IPs.

## Description
Copied binary of 'lsof' command version 4.8.9 from Ubuntu Server 17.10.1 i386
Lists open files, network connections, and ports of running processes.
It has several options of what to show, but by default, it shows all open files 
belonging to all active processes

This version of lsof is not statically linked (To-do: fix that)


## Usage
### Commands
Quick command adequate for now.


### Options
* -ips - Do not resolve IPs into hostnames


## Review
Lsof produces an enormous amount of data to read.  Finding anything in there is 
like finding a needle in a haystack, so look for other signs of compromise 
that can be linked to a program, file, IP address, or port.  Then search lsof 
for that.

## Location
Part of the linux-x86 tools image.


## Source
Version copied from fresh install of Ubuntu 17.10.1 Server i386
https://www.ubuntu.com/server


