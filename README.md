l4d2_structs
============

These are some simple C-style struct definitions which are formatted for use with IDA for examining Left 4 Dead 2's server binaries.

All information about these data structures and their members was obtained through one of two methods:

1. Reading publicly available class data in the Half Life 2 SDKs
2. Reverse engineering Left 4 Dead 2 server and/or client binaries

Note that no code has been copied from the HL2SDKs, only variable offset information. 

The reverse engineering involved in this project was done in order to support interoperability between the L4D2 server code and third party plugins. It should be protected under the DMCA.

Usage
=====
In IDA, go to File -> Load File -> Parse C Header File or hit Ctrl+F9.

Then, select l4d2_linux.h or l4d2_windows.h depending on which platform's server binary you are reading.


LuxLuma fork:

Windows offsets have not been maintained at all they are all likely wrong

Credits:
silvershot fixing errors that would happen from main repo.