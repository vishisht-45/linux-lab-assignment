\## 1. File Creation

\*\*Command:\*\*

```bash

echo "This is sample data for link testing." > sample\_data.txt

Explanation:

This command creates a file named sample\_data.txt in my home directory and writes sample text into it.





\## 2. Hard Link Creation

\*\*Command:\*\*

```bash

ln sample\_data.txt sample\_hard.txt

Explanation:

This command creates a hard link named sample\_hard.txt that points to the same data as sample\_data.txt.





\## 3. Symbolic Link Creation

\*\*Command:\*\*

```bash

ln -s sample\_data.txt sample\_soft.txt

Explanation:

This command creates a symbolic (soft) link named sample\_soft.txt that points to the original file sample\_data.txt.





\## 4. Inode Verification

\*\*Command:\*\*

```bash

ls -i sample\_data.txt sample\_hard.txt sample\_soft.txt

Explanation:

This command displays the inode numbers of the original file, hard link, and symbolic link.





\## 5. Inode Analysis



\*\*Explanation:\*\*  

The files sample\_data.txt and sample\_hard.txt share the same inode because a hard link points to the same data on disk. The symbolic link sample\_soft.txt has a different inode because it only stores the path to the original file.





\## 6. File Metadata Inspection

\*\*Command:\*\*

```bash

ls -l sample\_data.txt

Explanation:

This command displays detailed metadata of sample\_data.txt, including file permissions, ownership, size, and timestamps.





\## 7. Disk Usage Check

\*\*Command:\*\*

```bash

du -sh ~

Explanation:

This command shows the total disk space used by my home directory in a human-readable format.





\## 8. File Size Overview

\*\*Command:\*\*

```bash

ls -lh ~

Explanation:

This command lists all files in my home directory along with their sizes in a human-readable format.





\## 9. Link Deletion Test

\*\*Command:\*\*

```bash

rm sample\_soft.txt

ls sample\_data.txt

Explanation:

This command deletes the symbolic link sample\_soft.txt. The original file sample\_data.txt remains unaffected, showing that symbolic links do not store actual data.





\## 10. Disk Utility Demonstration

\*\*Commands:\*\*

```bash

du -h --max-depth=1 ~

df -h

Explanation:

The du command displays disk usage of directories in my home folder in a human-readable format. The df command shows overall disk space usage of filesystems, including total, used, and available space.







