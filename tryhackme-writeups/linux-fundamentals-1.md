# ✍️ TryHackMe Writeup: Linux Fundamentals Part 1

- **Platform:** TryHackMe
- **Room Link:** [Linux Fundamentals Part 1](https://tryhackme.com/room/linuxfundpart1)
- **Category:** Operating Systems / Fundamentals
- **Difficulty:** Easy
- **Date Completed:** October 2026

---

## 📌 Summary & Key Concepts
This room provides an introduction to the Linux operating system, running basic shell commands, and navigating the file system using the command-line interface (CLI). Understanding Linux CLI is essential for cybersecurity operations, system administration, and log analysis.

---

## 🛠️ Key Commands & Tools Learned

| Command | Description | Example Usage |
| :--- | :--- | :--- |
| `echo` | Prints text or variables to the terminal output | `echo "Hello World"` |
| `whoami` | Displays the current logged-in username | `whoami` |
| `ls` | Lists files and directories in the current folder | `ls -la` |
| `cd` | Changes the current working directory | `cd /var/log` |
| `cat` | Concatenates and displays contents of a file | `cat flag.txt` |
| `pwd` | Displays the absolute path of the current directory | `pwd` |
| `find` | Searches for files based on name or criteria | `find . -name "*.txt"` |

---

## 🔍 Room Breakdown & Walkthrough

### 1. Introduction & Running Your First Commands
- Connected to the target machine via the TryHackMe AttackBox / In-Browser Terminal.
- Verified terminal interaction using `echo` and `whoami`.

### 2. Navigating the File System
- Explored the filesystem structure using `pwd` to confirm location and `ls` to list directory contents.
- Used `cd` to move between relative and absolute directory paths.
- Used the `-a` flag with `ls` (`ls -a`) to reveal hidden files (files beginning with a dot `.`).

### 3. Reading & Searching Files
- Used `cat` to output text files directly to the terminal.
- Used `find` and `grep` to locate specific files and string occurrences within directories.

---

## 💡 Key Takeaways
- **Command Line Mastery:** Linux relies heavily on CLI navigation; knowing how to efficiently locate and view files without a GUI is critical for security investigations.
- **Hidden Files:** Security operators must always check for hidden configuration or artifact files using flags like `ls -la`.
- **System Structure:** The root `/` directory houses essential system folders like `/etc` (configurations), `/var` (logs/variable data), and `/home` (user profiles).
