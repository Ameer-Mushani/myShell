This program mimic the behaviour of a Linux shell but doesn't support full functionality.
On compatabile with Linux.

#Attribution:
Certain sections of this code is credited to Deb Stacey, with permission.

#Functionality:
 This program support running bash commands with any number of arguments.
    e.g ls -a

    The program also support input and output redirection as well as piping
    e.g ls | wc
    e.g cat ameer.txt > ameer2.txt

    The program includes support for built-in commands history, cd

    Additonally can echo environment variables from this shell : PATH, HOME,HISTFILE

Does not support export command or chaining redirects or chaining piping.

Background support is limited, commands run in the background but will not print when terminated.

#Compilation
$ make

#Execution
./myShell
Then use as you would a bash shell.
