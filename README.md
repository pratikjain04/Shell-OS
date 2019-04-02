# Shell-OS
Shell built in C, running all the basic commands.


### Usage Instructions:

get shell executable first:

gcc shell.c -o myshell
create run executable then - gcc run.c -o pnpshell
Usage - ./pnpshell

### Instructions supported in PnPShell :
*  cd <dir>                                 
*  pwd                                     
*  mkdir <dir>                            
*  rmdir <dir>                              
*  ls (support ls -l)                      
*  cp <file1> <file2>                      
*  exit                                     
*  execute any other command like ./a.out   
* support background execution - &          
* redirect input output >, <                
*  a.out | b.out - must support a| b| c     
* Additional - clear
* Additional - screenfetch
* Additional - up down keys, history- ?
* Additional - tab keys autocompletiton
