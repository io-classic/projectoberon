# projectoberon
Files retrieved from www.projectoberon.com with some utility modules added to complete the build process.

The source files are in original Oberon Text format, with CR line endings instead of LF, suitable for use in an un-modified Oberon system.
Binary files (.rsc and .smb,) fonts and Tool texts and an Inner Core binary file (`_BOOTIMAGE_`) are included, providing all the file content needed to create an Oberon disk image.  

To view the files in a Unix system you can convert the files like this:
* Carriage Return to Newline -->  `cat Example.Mod | tr '\r' '\n' > Example.Mod.NL`
* Newline to Carriage Return -->  `cat Example.Mod.NL | tr '\n' '\r' > Example.Mod.NL`

