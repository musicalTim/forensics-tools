# ISO Tools Images

## Description
Forensics tools intended for the target computer reside on ISO images that can 
be burned to discs or mounted in virtual machines.

These images were created with 
`genisoimage -iso-level -3 -r -o <output file> <input directory>`.
The options here allow lowercase and normal-length filenames and set execute permissions.


## Usage
Copy this file into the folder, name it after the tool it describes, and fill
in the blanks.


## Review
Images require maintenance - adjust them and update them from time to time as 
needed.


## Images
* linux-x64.iso - BusyBox (32-bit) and other live analysis tools (64-bit)
* linux-x86.iso - BusyBox (32-bit) and other 32-bit live analysis tools
* windows-xp.iso - Collection of 32-bit Windows tools for a Windows XP exercise
* windows10-x64.iso - Collection of 64-bit Windows tools originally created for an instructional video


## Source
The images themselves have been created for personal use and have not been distributed.


[Index](index.md)
