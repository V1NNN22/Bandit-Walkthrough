```markdown
# Written by: VINOD .N. RATHOD  

# Bandit Walkthrough — Level 26 → Level 27  

# Date: 24-08-2025  

## Objective  
Gain access to the password of "bandit27".  
Unlike previous levels, this stage provides no explicit hints. We need to investigate the files available and discover how to escalate privileges.  
```

## **Steps to Solve**

### Step 1 — Explore the Directory

1. After logging in as **bandit26**, list the available files:

```bash
   ls
```

Output shows:

```
bandit27-do
```

→ This is a special executable file.

---

### Step 2 — Inspect the Program

2. Execute the script without arguments:

```bash
   ./bandit27-do
```

Output provides an example of how to use it:

```
Run a command as another user.
Example: ./bandit27-do id
```

→ This indicates that the program allows us to run commands as **bandit27**.

---

### Step 3 — Confirm User Context

3. Verify which user the script runs commands as:

```bash
   ./bandit27-do whoami
```

Output:

```
bandit27
```

→ Confirmed: any command given is executed as user **bandit27**.

---

### Step 4 — Retrieve the Password

4. Use the script to read the password file of **bandit27**:

```bash
   ./bandit27-do cat /etc/bandit_pass/bandit27
```

This reveals the password for **bandit27**.

---
![Listing bandit27-do, help output, running whoami, reading password file, and SSH login](Assets/level-26.png)

### Step 5 — Connect as bandit27

5. With the password retrieved, log in as **bandit27**:

```bash
   ssh bandit27@bandit.labs.overthewire.org -p 2220
```


## **Outcome**

* Identified and used the **bandit27-do** helper program.
* Learned how to execute commands as another user.
* Retrieved the password for **bandit27**.
* Successfully logged into the next level.

---

# THANK YOU!

# \~ **V1NNN22** \~


