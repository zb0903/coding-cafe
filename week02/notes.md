1. pwd, which stands for present working directory, printed the path of the current directory. It indicates which folder my system is currently working in.

2. ls -a lists all the files and directories, including hidden ones, present in the current directory, while ls lists only the non-hidden files and directories.

3. The first column from 'ls -l' shows the type of file and its permissions. The first character indicates whether it is a file (-) or directory (d), while the remaining characters show who can read, write or execute the file.

4. It works because coding-cafe/week02 is a path starting from the current directory. The shell looks for coding-cafe/week02 inside the current directory in which it is working. This is a relative path because it does not start from the root directory (/).

5. mv was used first to move README-backup.md from the coding-cafe folder into week01. It was then used to rename README-backup.md to old-readme.md.

6. There are 18 directories on my PATH.

7. My python3 is located at /usr/bin/python3.

8. Our paths are different because the PATH depends on the programs installed on each computer and how those programs were configured. Different users may therefore have different folders included in their PATH.

9. The shell said Command 'pyton3' not found because pyton3 is not the correct command and there is no program with that name in my PATH. The PATH tells the shell which folders to search for a command, so it could not find pyton3 in any of them.

10. .venv did not appear with plain ls because its name starts with a dot, making it a hidden directory. The -a option shows hidden files and directories.

11. The prompt now starts with (.venv), showing that the virtual environment is active. This lets me know that commands such as python3 and pip will use the virtual environment.

12. No, the paths are different. Activating .venv changed my PATH so that the .venv/bin folder is searched first, meaning python3 now points to the Python inside the virtual environment.

13. The second list contains requests, certifi, charset-normalizer, idna, and urllib3, which were not in the first list. These packages were installed when I installed requests.

14. After deactivating the virtual environment, python3 points to /usr/bin/python3 again. This shows that deactivating restored my original PATH and system Python.

15. ls -h displays file sizes in a human-readable format, such as KB, MB, or GB, instead of just showing the size in bytes.

16. Ctrl + C interrupts the command or process that is currently running, but it does not necessarily exit the program. Ctrl + D signals the end of input and, in the Python interpreter, exits Python and returns to the terminal.