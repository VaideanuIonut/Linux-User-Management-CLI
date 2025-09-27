# Project Bash – User Login/Logout and Query System

**Technologies:** Bash scripting, Linux, PuTTY

## Description
This project implements a simple system for:
- User registration
- Login / Logout
- Generating a report of authenticated users

Data is stored in a CSV file (`utilizatori.csv`) and in local files.
The project was developed and tested in **PuTTY**, on a shared course server.

## Output Examples
Real results of the script can be found in the `output` folder.

## Observations
- The script automatically creates home directories for each user.
- Passwords are encrypted using SHA256.

## Main Menu Options
![Main Menu](</Meniul Principal.png>)
- Registration is done by selecting option 1 from the menu and entering a username, a valid email address, a password, and confirming it.
- Login is performed by selecting option 2 from the menu and entering an existing username from the `utilizatori.csv` file (already registered), along with the corresponding user password.
- Logout is done by selecting option 3 and entering the username.
- Selecting option 4 displays the list of users who are currently authenticated.
- Generating a user report is performed by selecting option 5 and automatically creates the `raport.txt` file after entering the username. This report contains information regarding the number of files, the number of directories of the user, the size they occupy on disk, along with the date and time the report was generated.
- Option 6, named `Iesire` (Exit), stops the script from running.