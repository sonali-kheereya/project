# project
Save and exit:

Press Esc to exit insert mode.
Type :wq and press Enter to save and quit.
Make the script executable:

sh
Copy code
chmod +x greet_user.sh
Run the script:

sh
Copy code
./greet_user.sh
Explanation:
date +%H: This command retrieves the current hour in 24-hour format (00 to 23).
The script uses conditional statements (if, elif, else) to determine the appropriate greeting based on the hour.
echo $greeting: This command prints the greeting to the terminal.
Running the Script Automatically on Login:
If you want this script to run automatically whenever you open a new terminal session, you can add it to your .bashrc or .profile file:

Edit your .bashrc or .profile:

sh
Copy code
vi ~/.bashrc
or

sh
Copy code
vi ~/.profile
Add the script execution command at the end of the file:

sh
Copy code
~/path/to/greet_user.sh
Save and exit:

Press Esc to exit insert mode.
Type :wq and press Enter to save and quit.
Source the file to apply changes:

sh
Copy code
source ~/.bashrc
or

sh
Copy code
source ~/.profile
Now, the greeting script will run automatically each time you start a new terminal session, providing a greeting based on the current system time.
