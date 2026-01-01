\## 1. System Uptime Verification

\*\*Command:\*\*

```bash

uptime

Explanation:

This command displays the time elapsed since the system was last booted along with basic system load information.





\## 2. User Process Listing

\*\*Command:\*\*

```bash

ps -u $USER

Explanation:

This command lists all processes currently running under my user account.





\## 3. CPU Usage Analysis

\*\*Command:\*\*

```bash

top

Explanation:

This command displays running processes in real time and helps identify the process consuming the highest CPU usage.





\## 4. Background Process Execution

\*\*Command:\*\*

```bash

sleep 300 \&

jobs

Explanation:

This command starts a process in the background, and the jobs command confirms that the background process is running.





\## 5. Process Priority Management

\*\*Command:\*\*

```bash

renice 5 -p 2647

Explanation:

This command changes the niceness value of a running process, reducing its priority so it consumes less CPU.





\## 6. Memory Usage Monitoring

\*\*Command:\*\*

```bash

free -h

Explanation:

This command displays memory usage statistics in a human-readable format, including total, used, and available memory.







\## 7. Disk Space Inspection

\*\*Command:\*\*

```bash

df -h ~

Explanation:

This command shows disk space usage of the filesystem containing my home directory, including total, used, and available space.





\## 8. Shell Identification

\*\*Command:\*\*

```bash

echo $SHELL

Explanation:

This command displays the name and path of the shell currently being used.





\## 9. Output Redirection

\*\*Command:\*\*

```bash

uname -a > system\_report.txt

Explanation:

This command redirects the output of a system information command into the file system\_report.txt.





\## 10. Disk Usage Visualization

\*\*Command:\*\*

```bash

ncdu ~

Explanation:

The ncdu command provides an interactive, visual representation of disk usage, helping identify large files and directories consuming disk space.

