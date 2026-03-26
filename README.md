# Linux

**sudo -i** -->
sudo -i starts a login shell as the root user.
It behaves as if root has logged in directly, loading root’s environment variables, PATH, and profile settings.

**cd**
cd stands for change directory.
It is used to move from your current working directory to another directory in the Linux filesystem.

**cd ..**
cd .. moves one directory up from your current location.
In Linux:
. = current directory
.. = parent directory (one level above)

**vi <fileName>**
This command opens the file <fileName> in the vi editor, which is a powerful text editor available on almost all Linux/Unix systems.
If the file exists, vi opens it for editing.
If the file does not exist, vi creates a new file with that name.

**ls**
ls lists all files and directories in your current working directory.

**netstat -tulpn**
This command displays all active TCP/UDP ports, along with the programs using those ports.
-t	Show TCP connections.
-u  Show UDP connections.
-l  Show listening ports only.
-p  Show PID/Program name using the port.
-n  Show addresses numerically (no DNS lookup).

**pwd**
Displays the absolute path of the current working directory.

**yum install <packagename> -y**
Installs the specified package using YUM and auto-accepts all confirmation prompts.

**name --version**
Displays the installed version and runtime details on the system.

**df -h**
Check the disk storage usage of the server

ps -ef
Displays a full, detailed list of all running processes on the system.

kill -9 <pid>
Forcefully terminates the process with the specified PID, without allowing it to shut down cleanly.

top
Displays a real-time, dynamic view of running processes, including CPU and memory usage.

rm -rf
Removes directories and their contents recursively (-r) while prompting for confirmation before each removal (-t/interactive-like behavior depending on system tools).

rmdir <directoryName>
Deletes a directory only if it is empty.

rmdir <directoryName>
Deletes a directory only if it is empty.

vi<filename>    
:wq
Opens or creates a file in the vi text editor for editing.

vi <filename>
:wq!
Forcefully write (save) the file and quit the vi editor, overriding any restrictions.

cat
Displays the contents of a file in the terminal.

ping google.com
Sends continuous network packets to google.com to check network connectivity and response time.

cd ~
Moves to the current user’s home directory.

uptime
Shows how long the system has been running, along with the current time, number of users, and system load averages.

history
Displays a list of previously executed commands in the terminal.

curl <link>
Transfers data from or to a URL, allowing you to download or interact with web content from the command line.

head -n 100 <filename>
Displays the first 100 lines of the specified file.

tail -n 100 <filename>
Displays the last 100 lines of the specified file.








