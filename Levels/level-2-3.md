````markdown
# Written by: VINOD .N. RATHOD  

# Bandit Walkthrough — Level 2 → Level 3  

# Date: 19-08-2025  

## Objective  
Retrieve the password for bandit3, which is stored in a file named `-- spaces in this filename --`.  
````
## **Steps to Solve**  
1. After logging in as **bandit2**, list the files in the current directory:  
```bash
   ls
```  

2. You will see a file named `--spaces in this filename--`.  
3. If you try:  
```bash
   cat spaces in this filename
```  
the command will fail because the shell interprets spaces as separate arguments.  

4. To correctly read the file, enclose the filename in quotes:  
```bash
   cat "./-- spaces in this filename --"
```  
5. This will display the password for **bandit3**.  

![Listing files, reading 'spaces in this filename', and showing the password](Assets/level-2.png) 

6. Use the password to log in as **bandit3**:  
```bash
   ssh bandit3@localhost -p 2220
```  

## **Outcome**  
* Successfully retrieved the password from the file `spaces in this filename`.  
* Logged into the server as **bandit3**.  
---
# THANK YOU!
#  ~ **V1NNN22** ~

