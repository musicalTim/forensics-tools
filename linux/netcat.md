# Netcat

## Quick Command
Forensic computer `nc -v -l -p 11111 >> test.txt`
Target computer `echo "test" | ./busybox-i686 nc <forensic ip> 11111`


## Description
Send data from standard in through a network connection, or recieve data from 
the network and write it somewhere.


## Usage
The quick commands will set up and test a "Netcat Pipe", a minimally intrusive 
means of getting data off the target computer without writing any files.

Take care whether you direct output using '>' or '>>'.  Start a new pipe with a 
new output file for each command you execute or file you transfer from the 
target computer.

Netcat will work for text, text files, and binary files.

Do take hashes of files before (if applicable) and after copying to ensure they 
are not damaged in transit.


## Review
It doesn't encrypt data, but it does exactly what it's meant to do.  Be careful 
to use it correctly to avoid overwriting something important.  Read twice, 
execute once.


## Location
For the target computer, use the nc command provided by [BusyBox]

[BusyBox]: busybox.md


## Source
* https://www.busybox.net/
* nc in Ubuntu is related to BSD Netcat (https://www.freebsd.org/cgi/man.cgi?query=netcat)

[Linux](linux.md)
