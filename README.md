# BashCyclone
A Bash script with a variety of Linux commands usable through a basic UI

What started as AdminScriptStarter that was made for an assignment for my Operating Systems class at Assumption University is now BashCyclone!

The first 11 menus in the script were made for the assignment but I wanted to add more options and make the shell script do more things.

Beyond the simple parts of the script I made for the assignment, I wanted to add more crazy scripts that could be easily executed.

In a perfect scenario, I want BashCyclone to be a teaching tool for the many aspects of Linux. With it, people can use Linux as they learn, and then view the code to see the commands when they want to learn how to use the command-line independently.

Then they'll be a force to be reckoned with! Almost like a cyclone..._a BashCylone_...I'll see myself out.




Some Useful Ideas to Implement:

Add root user to system [add this to Users Operations]

Nmap Scan (DONE)
^open ports, close ports etc

Systemctl Interface [start, stop, enable, disable services, see what services are running]

crontab Interface [see what tasks are scheduled, add, remove tasks scheduled]

at Interface *groan* [same as crontab, but annoying because crontab is just better]

And then maybe some crazier more destructive scripts for offensive purposes:

Delete all users except root [input which user to be saved, probably the one you have access to, if input blank, delete all]

Self-Destruct option [okay maybe not, but maybe who knows, probably just rm -rf /*]





Instructions for Download and Use:

Step 1:

Download the BashCyclone.sh

Step 2:

Navigate to /home/<user>/Downloads (where <user> is your username)

sudo su -

cd /home/<user>/Downloads

Step 3:

Use chmod to make the file executable by root:

sudo chmod 700 BashCyclone.sh

Step 4:

Move the file to a place where it is easiest to access. I prefer the Desktop

cd ..

mv Downloads/BashCyclone.sh Desktop

Step 5 (or to run from now on):

Run BashCyclone.sh as root in the directory you placed it in.

bash BashCyclone.sh
