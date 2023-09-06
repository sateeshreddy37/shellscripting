### The Shell Of Linux
 - Linux Has variety of Different Shells following:
   1. Bourne shell (sh),
   2. C shell (csh), 
   3. Korn shell (ksh), 
   4. TC shell (tcsh), 
   5. Bourne Again shell (bash).
 - Certainly most popular shell "BASH". its sh compatible shell that incorporates feature from k shell (ksh) and c   shell (csh)
 - It offers functional improvements over sh for both programming and interactive use.
### Programming or Scripting ?
 • bash is not only an excellent command line shell, but a scripting language in itself. Shell scripting allows us to use the shell's abilities and to automate a lot of tasks that would otherwise require a lot of commands.
 • Difference between programming and scripting languages:
 – Programming languages are generally a lot more powerful and a lot faster than scripting languages. Programming languages generally start from source code and are compiled into an executable. This executable is not easily ported into different operating systems.
 – A scripting language also starts from source code, but is not compiled into an executable. Rather, an interpreter reads the instructions in the source file and executes each instruction. Interpreted programs are generally slower than compiled programs. The main advantage is that you can easily port the source file to any operating system. bash is a scripting language. Other examples of scripting languages are Perl, Lisp, and Tcl.
### The first bash program
 • There are two major text editors in Linux:
 – vi, emacs (or xemacs).
 • So fire up a text editor; for example:
   $ vi &
 and type the following inside it:
  #!/bin/bash
    echo “Hello World”
 • The first line tells Linux to use the bash interpreter to run this script. We call it
   hello.sh. Then, make the script executable:
   $ chmod 700 hello.sh
   $ ./hello.sh
      Hello World
