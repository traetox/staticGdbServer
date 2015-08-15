# staticGdbServer
A set of statically built gdbserver binaries of various architectures
Should be good to just shove to your device and roll.  New additions ALWAYS welcome.

## Organization
Each directory is labeled with a base architecture, whith subdirectories describing
the specific architecture and version of gdb used during the build

## Licensing
gdb is licensed under GPLv2.  If any modifications to gdb were required
in order to complete the build, the entire gdb source tree MUST be included
in the subdirectory.  If no modifications were made to the source a link
pointing to the version of gdb used will be provided in a NOTES file.

## Housekeeping
All binaries are stripped to reduce size
