0x05 Processes and signals 🔧
Using a shell script is most useful for repetitive tasks that may be time consuming to execute by typing one line at a time. A few examples of applications shell scripts can be used for include: Automating the code compiling process. Running a program or creating a program environment. This project covers processes and signals

At the end of this project, I was able to solve these questions:

What is a PID
What is a process
How to find a process’ PID
How to kill a process
What is a signal
What are the 2 signals that cannot be ignored
Tasks ✔️
Script that displays its own PID.
Script that displays a list of currently running processes.
Script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
Script that displays the PID, along with the process name, of processes whose name contain the word bash.
Script that displays To infinity and beyond indefinitely.
Script that kills 4-to_infinity_and_beyond process.
Script that that kills 4-to_infinity_and_beyond process. v2
Script that displays 'To infinity and beyond' indefinitely with a sleep 2 in between each iteration 'I am invincible!!!'' when receiving a SIGTERM signal
Script that kills the process 7-highlander.
Script that creates the file /var/run/holbertonscript.pid containing its PID
Script that indefinitely writes I am alive! to the file /tmp/my_process
C program that creates 5 zombie processes.
Additional info 🚧
Resources
BASH
Ubuntu 20.04 LTS
Shellcheck 0.7.0
betty linter
Try It On Your Machine 💻
git clone https://github.com/ZoeDioDrey/alx-system_engineering-devops.git
cd 0x05-processes_and_signals
cat FILENAME
./FILENAME
FOR C SCRIPTS
gcc -Wall -Werror -Wextra -pedantic FILENAME.c -o FILENAME
