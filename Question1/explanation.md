1\.**User Identity Verification**

&nbsp;	**Command** : id

**Explanation:**

&nbsp;	This command displays my currently logged-in username and all groups my user account belongs to, verifying my user identity.







**2.Workspace Validation**

&nbsp;	**Command** : pwd

&nbsp;		  ls -l

**Explanation:**

	The pwd command displays the current working directory, confirming my workspace. The ls -l command lists all files and directories in long format, showing permissions and ownership details.







**3. Environment Confirmation File**

&nbsp;	**Command:** echo "Linux user environment verified" > user\_info.txt

**Explanation:**

&nbsp;	This command creates a file named user\_info.txt and writes the text “Linux user environment verified” into it.





**4. File Integrity Check**

	**Command**: wc -c user\_info.txt

**Explanation:**

&nbsp;	This command displays the total number of characters present in the user\_info.txt file.





**5. Learning the Tools**

	**Command:** man mkdir

**Explanation:**

&nbsp;	This command opens the manual page for mkdir. One useful option is -p, which allows creation of parent directories if they do not already exist.





**6. Home Directory Inspection**

	**Command:** ls ~

**Explanation:**

&nbsp;	This command lists the contents of my home directory in alphabetical order.





**7. Log Investigation**

	**Command:** grep "admin" log.txt

**Explanation:**

&nbsp;	This command searches for the word "admin" in the log.txt file and displays only the matching lines.





**8. System Information Check**

	**Command:** uname -r

**Explanation:**

&nbsp;	This command displays the version of the Linux kernel currently running on the system.




## 9. Network Connectivity Test
**Command:**
```bash
ping www.google.com

**Explanation:**
	This command sends ICMP echo requests to www.google.com to verify network connectivity and internet access.








