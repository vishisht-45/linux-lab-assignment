\## 1. Project Workspace Setup

\*\*Command:\*\*

```bash

mkdir documents

Explanation:

This command creates a directory named documents inside my home directory to store project-related files.







\## 2. File Creation

\*\*Command:\*\*

```bash

cd ~/documents

touch plan.txt

Explanation:

This command navigates into the documents directory and creates an empty file named plan.txt.







\## 3. Content Addition

\*\*Command:\*\*

```bash

echo "Complete the project documentation before deadline." > plan.txt

Explanation:

This command writes sample project-related text into the plan.txt file.





\## 4. File Metadata Verification

\*\*Command:\*\*

```bash

ls -l plan.txt

Explanation:

This command displays the permissions, ownership, size, and other metadata of the plan.txt file, confirming my user account as the owner.





\## 5. File Duplication

\*\*Command:\*\*

```bash

cp plan.txt plan\_copy.txt

Explanation:

This command creates a duplicate of plan.txt named plan\_copy.txt.





\## 6. Directory Renaming

\*\*Command:\*\*

```bash

mv documents project\_documents

Explanation:

This command renames the documents directory to project\_documents to better reflect the project scope.





\## 7. Archival Structure

\*\*Command:\*\*

```bash

mkdir project\_documents/archive

Explanation:

This command creates a subdirectory named archive inside the project\_documents directory.





\## 8. File Organization

\*\*Command:\*\*

```bash

mv project\_documents/plan\_copy.txt project\_documents/archive/

Explanation:

This command moves plan\_copy.txt into the archive subdirectory for proper file organization.





\## 9. Recursive Listing

\*\*Command:\*\*

```bash

ls -R project\_documents

Explanation:

This command lists all files and subdirectories inside project\_documents recursively, showing the complete directory structure.





\## 10. Path Verification

\*\*Command:\*\*

```bash

realpath project\_documents/archive/plan\_copy.txt

Explanation:

This command displays the absolute path of plan\_copy.txt after it has been moved to the archive directory.







