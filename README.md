# projectoberon
Files retrieved from www.projectoberon.com with some utility modules added to complete the build process.

The source files are in original Oberon Text format, with CR line endings instead of LF, suitable for use in an un-modified Oberon system.
Binary files (.rsc and .smb,) fonts and Tool texts and an Inner Core binary file (`_BOOTIMAGE_`) are included, providing all the file content needed to create an Oberon disk image.  

To view the files in a Unix system you can convert the files like this:
* Carriage Return to Newline -->  `cat Example.Mod | tr '\r' '\n' > Example.Mod.NL`
* Newline to Carriage Return -->  `cat Example.Mod.NL | tr '\n' '\r' > Example.Mod`


# License of the Project Oberon files

Project Oberon, Revised Edition 2013

Book copyright (C)2013 Niklaus Wirth and Juerg Gutknecht;
software copyright (C)2013 Niklaus Wirth (NW), Juerg Gutknecht (JG), Paul
Reed (PR/PDR).

Permission to use, copy, modify, and/or distribute this software and its
accompanying documentation (the "Software") for any purpose with or
without fee is hereby granted, provided that the above copyright notice
and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHORS DISCLAIM ALL WARRANTIES
WITH REGARD TO THE SOFTWARE, INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY, FITNESS AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS BE LIABLE FOR ANY CLAIM, SPECIAL, DIRECT, INDIRECT, OR
CONSEQUENTIAL DAMAGES OR ANY DAMAGES OR LIABILITY WHATSOEVER, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE DEALINGS IN OR USE OR PERFORMANCE OF THE SOFTWARE.


