# Create_OS_Kernel
just creating a basic kernel with x86_Assembly and C languages.


Requirements:
GNU/Linux :-  I am using GNU/Linux Ubuntu 16.04 LTS
Assembler :-  I am using GNU Assembler(NASM)
GCC :-  GNU Compiler Collection a cross compiler. gcc (Ubuntu 5.4.0-6ubuntu1~16.04.9) 5.4.0 20160609
Xorriso :-  A package that creates, loads, manipulates ISO 9660 filesystem images.(man xorriso)
grub-mkrescue :-  Make a GRUB rescue image, this package internally calls the xorriso functionality to build an iso image.
QEMU :-  Quick EMUlator to boot our kernel in virtual machine without rebooting the main system.

Let's Run:
- $chmod +x run.sh
- $./run.sh



referances:
- https://www.youtube.com/watch?v=l2wZf45ZcAg
- http://createyourownos.blogspot.com.tr/
- https://www.codeproject.com/Articles/1225196/Create-Your-Own-Kernel-In-C
