The memory access traces of five Linux Xwindows applications were captured by using a modified version of the Cachegrind tool from the Valgrind toolset. 
Each trace file contains three columns: reference type, virtual address, and access size.
The reference type column can be one of instruction read (readi), data read (readd), or data write (write).
The virtual address column is listed in hexadecimal.
The access size is listed in bytes. 

The following is an example of a trace file.

```
readi	0x04000BE0	2
write	0xBEFFFACC	4
readi	0x04000C30	1
write	0xBEFFFABC	4
readd	0x0401582C	4
:	:		:
```
