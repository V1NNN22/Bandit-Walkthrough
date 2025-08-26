# Bandit-Walkthrough - V1NNN22
“OverTheWire Bandit Walkthrough – step-by-step solutions for all 33 levels with explanations &amp; commands.”

```markdown
# OverTheWire — Bandit Walkthrough  

# Written by: VINOD .N. RATHOD 

This My repository contains my complete walkthrough of the "OverTheWire Bandit Wargame", covering all levels from "Level 0 → Level 33".  
The Bandit game is designed for beginners to learn "Linux basics, file system navigation, permissions, networking, Git, and privilege escalation techniques" in a practical, hands-on way.  
````
## 📖 Level Overview  
### Level 0 → Level 5 — Getting Started  
* **Topics:** SSH basics, file listing, hidden files, filenames with special characters, spaces, etc.  
* **Skills Learned:**  
  * Connecting via SSH with username/password.  
  * Using `ls`, `cat`, and relative paths.  
  * Handling tricky filenames (`./-`, spaces in filenames, hidden files).  
---
### Level 6 → Level 10 — File Searching & Filtering  
* **Topics:** Finding files, file types, and filtering content.  
* **Skills Learned:**  
  * `find` with size, user, group filters.  
  * Using `grep` with pipes.  
  * `strings` for extracting readable text.  
  * Sorting and deduplicating with `sort` + `uniq`.  
---
### Level 11 → Level 15 — Encoding & Networking Basics  
* **Topics:** Encodings (Base64, ROT13), compressed files, network connections.  
* **Skills Learned:**  
  * `base64 --decode`, `tr` for ROT13.  
  * Decompressing multiple archive formats (`gzip`, `bzip2`, `tar`).  
  * Using private SSH keys.  
  * Interacting with services over **telnet** and **openssl**.  
---
### Level 16 → Level 20 — Ports & Services  
* **Topics:** Port scanning, OpenSSL, RSA private keys, setuid binaries.  
* **Skills Learned:**  
  * Using `nmap` to discover services.  
  * Connecting to SSL services with `openssl s_client`.  
  * Creating and using private RSA keys.  
  * Handling multi-session tasks with `netcat` + `suconnect`.  
---
### Level 21 → Level 25 — Cron Jobs & Automation  
* **Topics:** Cron jobs, temporary directories, brute forcing.  
* **Skills Learned:**  
  * Reading `/etc/cron.d` and cron scripts.  
  * Extracting hidden passwords from cron jobs.  
  * Using `md5sum` tricks.  
  * Writing custom shell scripts.  
  * Brute forcing 4-digit codes with bash loops and `netcat`.  
---
### Level 26 → Level 33 — Git & Restricted Shells  
* **Topics:** Git forensics, branches, tags, commit history, restricted shells.  
* **Skills Learned:**  
  * Cloning Git repos over SSH (`ssh://user@localhost:2220/...`).  
  * Exploring history with `git log` and `git show`.  
  * Switching branches (`git checkout dev`).  
  * Reading Git tags (`git tag`, `git show tagname`).  
  * Pushing changes to trigger remote validation.  
  * Escaping restricted shells (`$0` trick).  
  * Completing the final level (`README.txt`).  
---
## 🏆 Key Takeaways  
* Linux basics: permissions, hidden files, handling special filenames.  
* Networking: SSH, telnet, netcat, SSL, nmap.  
* Encoding/decoding: Base64, ROT13, hex dumps, compressed archives.  
* Git forensics: commits, branches, tags, pushing changes.  
* Scripting: brute forcing with bash loops.  
* Privilege escalation & restricted shell escape.  
---
## 📊 Status  
* **Completed Levels:** 0 → 33  
* **Current:** Waiting for OverTheWire team to release more Bandit levels.  
---
## 📂 Walkthrough Details  
Each level’s **full step-by-step commands, screenshots, and explanations** are documented in this walkthrough.  
* Written to be **professional, clean, and beginner-friendly**.  
* Suitable for **beginners and professionals**.  
----

# THANK YOU!
# \~ **V1NNN22** \~
