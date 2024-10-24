Paste the installation script into your terminal, add your 3 APY keys into the correct section of the script before you hit enter. 
To use the tool you have 4 commands

Python3 /usr/local/bin/netrecon/netrecon.py recon <enter_IP_Here>

Python3 /usr/local/bin/netrecon/netrecon.py trace <enter_IP_Here>

Python3 /usr/local/bin/netrecon/netrecon.py report <enter_IP_Here>

Python3 /usr/local/bin/netrecon/netrecon.py capture <enter_IP_Here>

The symlink and permissions for some reason to shorten the commands is faulty, so just use the full python3 commands for now until i fix that error
The capture function is still buggy as I need to find a way around a few things, just press ctrl+c to stop the capture
This is an ongoing project feel free to take the code and adjust it
The report command will print a report out, use locate report.txt file Id to find it and open in nano or whatever you use
