# Ubuntu_Learning

//Adding your shell scripts as commands for your command prompt. 

//When there is script file you have to open every day. It is better to use the shell script and add to the bin directory. 

1. Create a folder bin in your $HOME directory. 
       Ex: /home/nagendra/bin
2. Place your shell script go_ide.sh in bin folder

3. Add bin the $PATH of your system. 
    export PATH=$PATH:/home/nagendra/bin 
    
4. Source your profile file instead of logout and logon. 
    source ~/.profile
    
5. Execute go_ide.sh in your command prompt. 
