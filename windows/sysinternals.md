# Microsoft Sysinternals Suite: 2010 version

## Description
A collection of troubleshooting utilities provided by Microsoft, which includes 
several tools useful to forensics.


## Usage
From the command line, run the tool you need.  The first time each program 
runs, it will prompt you to accept a license in a GUI window.

Useful tools
* PSFile - Open files
* PSLoggedOn - Active remote login sessions
* PSList - Running processes
* PSServcie - Running services

The tools may not terminate their output with end-of-file, so if the command 
prompt does not return after ten seconds, stop it with `Ctrl + C`.  This is 
important if you are redirecting output to a [Netcat pipe](../linux/netcat.md).


## Review
The GUI popup is annoying, but these tools provide very useful functionality 
beyond what the Windows command prompt provides.


## Location
These executables are included in the windows10-x64 tools image.


## Source
https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite


## See Also
[Sysinternals Suite 2010](sysinternals-2010.md)


[Windows Forensics Tools](windows.md)
