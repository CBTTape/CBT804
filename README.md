# CBT804
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 804 is from Rich Hobt and contains a version of the       *   FILE 804
//*           TAPEMAP program from File 299 which was modified      *   FILE 804
//*           to use the modern "relative addressing" assembler     *   FILE 804
//*           instructions.  In other words, JUMP instead of        *   FILE 804
//*           BRANCH was used.  This freed up the need to fill a    *   FILE 804
//*           whole bunch of base registers.                        *   FILE 804
//*                                                                 *   FILE 804
//*           Some of Rich's new macros helped in the conversion:   *   FILE 804
//*              ASMINFO BR2JMP BR2JMPX INR OUTR                    *   FILE 804
//*                                                                 *   FILE 804
//*           Sam Golob added the new device types for FDR dump     *   FILE 804
//*           reporting, that were contributed to File 299 TAPEMAP  *   FILE 804
//*           by John Kalinich, with the help of (the late)         *   FILE 804
//*           Bruce Black of FDR Innovation.                        *   FILE 804
//*                                                                 *   FILE 804
//*           This version currently corresponds to Version 2.5     *   FILE 804
//*           of TAPEMAP on CBT File 299.  The reason why it was    *   FILE 804
//*           put into a separate file, is that MVS 3.8 people      *   FILE 804
//*           can't assemble the Jump instructions using the        *   FILE 804
//*           IFOX00 assembler, so this file was kept separate.     *   FILE 804
//*                                                                 *   FILE 804
//*           Added an XMIT of a load library which contains the    *   FILE 804
//*           following TAPEMAP versions:   (member LOADLIB)        *   FILE 804
//*                                                                 *   FILE 804
//*           member     CBT File    Version                        *   FILE 804
//*           ------     --------    -------                        *   FILE 804
//*           TAPEMAP      299        2.5                           *   FILE 804
//*           TAPEMAPM     299        2.5.1                         *   FILE 804
//*           TAPEMAPX     804        2.5.3                         *   FILE 804
//*                                                                 *   FILE 804
//*           email:  RHobt@azdps.gov                               *   FILE 804
//*                                                                 *   FILE 804
```
