# myOS
Welcome to myOS! myOS is comprised of a custom bootloader and kernel that together can handle very basic user interaction.

## Purpose
This operating system was a self guided project to get a better understanding
of how computers (and of course operating systems) function. I followed a multitude
of different tutorials to pull this together, resulting in the product you see here.

Lessons learned include: 
- Building a cross compiler (gcc i386-elf)
- Assembling assembly into object files
- Linking object files into binaries/executables
- Handling interupts at the OS level
- Writing drivers without any of the abstractions provided by standard libraries (which rely in part on the operating system)