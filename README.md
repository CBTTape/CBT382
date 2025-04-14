# CBT382
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 382 is from Paul Gillis of Melbourne, Australia, and      *   FILE 382
//*           contains a number of programs and utilities that      *   FILE 382
//*           he has developed.                                     *   FILE 382
//*                                                                 *   FILE 382
//*           Paul Gillis                                           *   FILE 382
//*           Director P.C. Link Pty. Ltd. &                        *   FILE 382
//*           Pacific Systems Management Pty. Ltd.                  *   FILE 382
//*           Melbourne, Australia                                  *   FILE 382
//*                                                                 *   FILE 382
//*   email:  "Paul Gillis" <pgillis@pc-link.com.au>                *   FILE 382
//*                                                                 *   FILE 382
//*         UNLOAD and UNLOAD$. The unload assembler program        *   FILE 382
//*         provides the ability to convert a PDS into a flat       *   FILE 382
//*         file and to insert a control card of your own           *   FILE 382
//*         making in between each unloaded member, with the        *   FILE 382
//*         member name inserted at any position in the record.     *   FILE 382
//*                                                                 *   FILE 382
//*         DASD. This SMP/E usermod provides a DASD LSPACE         *   FILE 382
//*         program, that dumps all the data returned by the        *   FILE 382
//*         LSPACE macro into a file for further analysis.          *   FILE 382
//*                                                                 *   FILE 382
//*         DASDSPCE. This SMP/E usermod provides a DASD space      *   FILE 382
//*         command that will display the available space on a      *   FILE 382
//*         selected subset of the dasd farm.                       *   FILE 382
//*                                                                 *   FILE 382
//*         DEBUG. This assembler macro I use to produce debug      *   FILE 382
//*         information from most programs that I write. The        *   FILE 382
//*         debug information is written to any number of           *   FILE 382
//*         possible output data sources.                           *   FILE 382
//*                                                                 *   FILE 382
//*         GRS. This SMP/E usermod provides a WHOHAS type          *   FILE 382
//*         utility, and is normally used for that purpose.         *   FILE 382
//*                                                                 *   FILE 382
//*         SYSTEM. This SMP/E usermod contains a system IPL        *   FILE 382
//*         details program, which includes system symbols.         *   FILE 382
//*                                                                 *   FILE 382
//*         DISASM. Members DISASJCL, DISASMAC and DISASSRC         *   FILE 382
//*         contain an updated version of the disassembler          *   FILE 382
//*         found on file 171. The update supports all of the       *   FILE 382
//*         two byte 01 and B2 instructions. Support was not        *   FILE 382
//*         added for the A4, A5, A6, E4 and E5 opcodes, but        *   FILE 382
//*         could now be added reasonably easily.  Instruction      *   FILE 382
//*         set based on SA22-7209-01 ESA/390 Reference Summary.    *   FILE 382
//*                                                                 *   FILE 382
//* 2009 additions                                                  *   FILE 382
//*                                                                 *   FILE 382
//*         DEBUGDOC documentation file for the DEBUG macor.        *   FILE 382
//*                                                                 *   FILE 382
//*         SHELL a very basic assembler program that I use as a    *   FILE 382
//*         model for any new code. This also contains samples of   *   FILE 382
//*         how the debug macro is coded.                           *   FILE 382
//*                                                                 *   FILE 382
//*         ISPFSTAT An assembler copy book that maps the ISPF stats*   FILE 382
//*         of a PDS directory, used by LISTDIR.                    *   FILE 382
//*                                                                 *   FILE 382
//*         LISTDIR  An assembler module to extract the contents of *   FILE 382
//*         a PDS directory. Used in IPL volume comparisons         *   FILE 382
//*                                                                 *   FILE 382
//*         LISTVTOC An assembler module to extract the contents of *   FILE 382
//*         a VTOC. Used in IPL volume comparisons                  *   FILE 382
//*                                                                 *   FILE 382
//*         IPLBLD00 JCL include meber to set both IPL Volsers      *   FILE 382
//*                                                                 *   FILE 382
//*         IPLBLD90 JCL deck to generate IPL vol PDS compare jobs  *   FILE 382
//*         and compares the VTOCs while at it.                     *   FILE 382
//*                                                                 *   FILE 382
//*         IPLBLD91 JCL deck generated by IPLBLD90 that actually   *   FILE 382
//*         compares all PDS directories on the 2 IPL volumes.      *   FILE 382
//*                                                                 *   FILE 382
//*         IPLCOMPR JCL proc to compare PDS directories            *   FILE 382
//*                                                                 *   FILE 382
//*         IPLVOLXP Rexx exec to build IPL vol PDS directories     *   FILE 382
```
