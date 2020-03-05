# RTDoor
Red Team NetCat Backdoor Service

Operating on port `1333`, change the backdoor.service file manually for more/differrent ports. 

Side note: In backdoor.service $CHANGEME will be changed when running the setup normally!

## Script Summary
The setup is very simple, just run the command:

`./setup`

This will edit the service and get it going for Red Team,
once enabled at anytime (even if Blue Team restarts their machines) the netcat command:

`nc ${HOST} 1337`

Will allow access unless Blue Team removes the temporary `nc` command or stops & disables / deletes the service. 

Happy Red Teaming :)
