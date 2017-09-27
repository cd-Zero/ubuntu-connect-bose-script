# ubuntu-connect-bose-script

## Issue:
  bose headphone have a issue connecting to bluetooth on ubuntu and several linux distrubutions. Running this command
  will allow bose headphones to connect.

# How to use:
 clone github repo
 
 mkdir ~/bin
 script_name can be any script name
 touch ~/bin/script_name
 
 chmod +x script_name
 
 // copy contents of script file into your script
 cat ubuntu-connect-bose-script/bose-script > ~/bin/script_name
 
 // allow .bashrc to run commands made in the ~/bin file
nano ~/.bashrc  

and enter following  command at bottom of file
  export PATH=$PATH:~/bin
  
  
  command should now work!
 
 
      
