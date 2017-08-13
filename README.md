# DracMem
Just Paste into your terminal

Bash function to get recognized memory size on dell servers via Drac-SSH

Requires: sshpass

Usage:

  To run against a file
  
    drac -f YourFileName
    
  To run against hosts via arguments
  
    drac 1.1.1.1 1.2.3.4 my-host.domain.corp

Will prompt for the Drac Password to use

if host is off it will prompt if you want to turn it back on

will output to file called "out"

Need to change:

  file output prompt + prompt file name (tee -a drac.$file)
