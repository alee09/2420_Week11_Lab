clone the git repo into your machine.

within the motd.service file you will need to change the *WorkingDirectory* and *ExecStart*.
  for *ExecStart* - copy and paste the current working directory by typing pwd in the console.
  for *WorkingDirectory* - take your working directory and add */motd* as it is the script file that the service will run on startup.
 
The timer does not need editing but will run the service hourly after startup.
