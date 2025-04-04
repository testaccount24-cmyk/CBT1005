# CBT1005
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1005 is from Peter Sylvester and contains his SPTS         *   FILE1005
//*           package of programs, otherwise known as               *   FILE1005
//*           Assembler Structured Programming Tool Set.            *   FILE1005
//*                                                                 *   FILE1005
//*     GMD-SPTS Distribution                                       *   FILE1005
//*                                                                 *   FILE1005
//*         This package has been brought to the CBTTAPE by         *   FILE1005
//*                                                                 *   FILE1005
//*         Peter Sylvester                                         *   FILE1005
//*         peter@edelweb.eu                                        *   FILE1005
//*                                                                 *   FILE1005
//*     SPTS is (whatever you prefer) :                             *   FILE1005
//*                                                                 *   FILE1005
//*               Structured Programming Tool Set                   *   FILE1005
//*               System Programmer's Tool Set                      *   FILE1005
//*               Sylvester Peter's Toy Set                         *   FILE1005
//*                                                                 *   FILE1005
//*        It has ee functional components :                        *   FILE1005
//*                                                                 *   FILE1005
//*          1: SPTS MACLIB                                         *   FILE1005
//*                                                                 *   FILE1005
//*             The core functionality are assembler macros for     *   FILE1005
//*             structured programming:                             *   FILE1005
//*                                                                 *   FILE1005
//*             - a large set of control flow statements            *   FILE1005
//*             - statement like conditional expressions            *   FILE1005
//*             - composition of expressions ($EX EX$ ORELSE,       *   FILE1005
//*               ANDTHEN)                                          *   FILE1005
//*             - basic comparison expressions ($EXPR$ and          *   FILE1005
//*               TRUECC)                                           *   FILE1005
//*             - assignment statements (LET)                       *   FILE1005
//*             - Organisation of code an static data using         *   FILE1005
//*               LTORG                                             *   FILE1005
//*                                                                 *   FILE1005
//*             Usage requires at least the SLAC version of ASMH.   *   FILE1005
//*                                                                 *   FILE1005
//*             The macros can be used without the other tools.     *   FILE1005
//*                                                                 *   FILE1005
//*          2 SPTS PCPARSER                                        *   FILE1005
//*                                                                 *   FILE1005
//*             A tool to work on structured pseudo code            *   FILE1005
//*             version of some software/program. PCPARSER          *   FILE1005
//*             transforms the pseudo code into an assembler        *   FILE1005
//*             skeleton and produces a documentation. The          *   FILE1005
//*             assembler skeleton is provided as IEBUPDTE          *   FILE1005
//*             input (program refinements are translated into      *   FILE1005
//*             COPYLIB members.                                    *   FILE1005
//*                                                                 *   FILE1005
//*             PCPARSER is written in STRUBOL, an enhanced         *   FILE1005
//*             version of SPITBOL. Source is included for          *   FILE1005
//*             inspiration.                                        *   FILE1005
//*                                                                 *   FILE1005
//*             The pseudo code combines                            *   FILE1005
//*             - a set of control flow statements                  *   FILE1005
//*               translated into corresponding macros              *   FILE1005
//*             - free form text as pseudo code                     *   FILE1005
//*               translated ton comments (actually @ macro)        *   FILE1005
//*                                                                 *   FILE1005
//*          3: SPTS SASLIST                                        *   FILE1005
//*                                                                 *   FILE1005
//*             A program acting of the assembler listing (SLAC     *   FILE1005
//*             version) to enhance readability. Using is not       *   FILE1005
//*             required.                                           *   FILE1005
//*                                                                 *   FILE1005
//*     The package (PDS) contains the following members:           *   FILE1005
//*                                                                 *   FILE1005
//*        $$README:                                                *   FILE1005
//*                                                                 *   FILE1005
//*             This member                                         *   FILE1005
//*                                                                 *   FILE1005
//*        $LICENCE:                                                *   FILE1005
//*                                                                 *   FILE1005
//*             Copyright and licencing, don't worry                *   FILE1005
//*                                                                 *   FILE1005
//*        CNTL (XMI packed PDS):                                   *   FILE1005
//*              A set of jobs for inspiration to install SPTS      *   FILE1005
//*              parts.                                             *   FILE1005
//*                                                                 *   FILE1005
//*        You can recover the content using the TSO commands:      *   FILE1005
//*                                                                 *   FILE1005
//*           ALLOC DA(SPTS.CBTTAPE) FI(RECEIVE)                    *   FILE1005
//*           RECEIVE INFILE(RECEIVE)                               *   FILE1005
//*                                                                 *   FILE1005
//*        EXAMPLES (XMI packed PDS):                               *   FILE1005
//*                                                                 *   FILE1005
//*              A small set of examples, assembler programs        *   FILE1005
//*              may not compile or link.                           *   FILE1005
//*                                                                 *   FILE1005
//*        INFO (XMI packed PDS):                                   *   FILE1005
//*                                                                 *   FILE1005
//*              German documentation                               *   FILE1005
//*                                                                 *   FILE1005
//*        LINKLIB (XMI packed PDS):                                *   FILE1005
//*                                                                 *   FILE1005
//*              The PCPARSER and SASLIST load modules.             *   FILE1005
//*                                                                 *   FILE1005
//*        MACLIB (XMI packed PDS):                                 *   FILE1005
//*                                                                 *   FILE1005
//*              The assembler structured macros                    *   FILE1005
//*                                                                 *   FILE1005
//*        PROCLIB (XMI packed PDS):                                *   FILE1005
//*                                                                 *   FILE1005
//*              A set of JCL procedures.                           *   FILE1005
//*                                                                 *   FILE1005
//*        SASLOBJ:                                                 *   FILE1005
//*                                                                 *   FILE1005
//*              A compiled SASLIST object                          *   FILE1005
//*                                                                 *   FILE1005
//*        SOURCE (XMI packed PSD):                                 *   FILE1005
//*                                                                 *   FILE1005
//*              The PCPARSER and SASLIST source                    *   FILE1005
//*                                                                 *   FILE1005
//*     Alles hat einmal ein Ende, nur die Wurst hat zwei.          *   FILE1005
//*     Everything comes to an end.  But for a sausage there are    *   FILE1005
//*        two.                                                     *   FILE1005
//*                                                                 *   FILE1005
```
