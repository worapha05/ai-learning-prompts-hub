# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Systems Engineer, Linux Kernel Architect, and Senior DevOps Administrator. Help me create a complete "Zero to Expert" self-learning bootcamp for Linux/Unix Commands and CLI operations, focusing on system mechanics, file system optimization, text processing pipelines, and production-grade Shell Scripting (Bash).

# Target Structure
Generate all files inside a folder named `/linux-unix-cli`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี โครงสร้างสถาปัตยกรรมของ Linux (Kernel, Shell, File System) และกลไกการทำงานของ OS อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน Shell Scripts (.sh), คำสั่ง One-liners ที่มีประโยชน์ และการคอนฟิกสภาพแวดล้อมระบบ (เช่น .bashrc / .zshrc)
3. `LAB.md`: โจทย์ทดสอบการแก้ไขปัญหาระบบ (Troubleshooting), การจัดการไฟล์คอขวด, และการเขียนสคริปต์ Automation จัดการข้อมูลจากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และสคริปต์อย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (File System Architecture & Essential Navigation)
- Linux Directory Structure: Understanding the Filesystem Hierarchy Standard (FHS) like `/etc`, `/var`, `/opt`, `/home`, and `/bin`.
- Command Line Essentials: Navigation and manipulation files (`pwd`, `ls`, `cd`, `mkdir`, `rm`, `cp`, `mv`, `touch`).
- Text Inspection & Redirection: Using `cat`, `less`, `head`, `tail`, and understanding Standard I/O streams (`stdin`, `stdout`, `stderr`) along with redirection operators (`>`, `>>`, `2>`).
- Package Management & WSL Environment: Using package managers (`apt`, `yum`) and optimizing development workflows inside WSL (Windows Subsystem for Linux).

## 2. Intermediate Level (Users, Security Permissions, & Text Processing Pipelines)
- Linux Security Model: Deep dive into File Permissions (`chmod` octal/symbolic) and Ownership (`chown`, `chgrp`). Understanding `sudo` mechanisms and root access constraints.
- Process Management: Inspecting and controlling system processes using `ps`, `top`, `htop`, `kill`, `killall`, and running background/foreground jobs (`&`, `bg`, `fg`, `jobs`).
- Text Manipulation & Data Filtering: The power of Pipes (`|`) combined with filter utilities: **grep** (regular expressions filtering), **awk** (column processing), **sed** (stream editing), `sort`, `uniq`, and `find` for locator patterns.
- Networking Utilities: Basic network inspection and testing endpoints using `ping`, `curl`, `wget`, `netstat`, `ss`, and checking open ports.

## 3. Expert Level (Advanced Bash Automation, System Performance, & Hardening)
- Production Shell Scripting (Bash): Writing professional scripts. Advanced variables, control structures (`if`, `for`, `while`), positional parameters, error handling (`set -e`, `set -o pipefail`), traps for teardown, and writing logs.
- Storage & Memory Profiling: Debugging disk space and memory leaks at the OS level using `df`, `du` (finding large directories), `free -m`, `vmstat`, and tracking file locks or system calls using `lsof` and `strace`.
- Task Automation & Shell Customization: Setting up automated cron jobs (`crontab`), understanding system daemons (systemd service creation), and optimizing remote headless server management via **SSH customization** (Config files, port forwarding, and secure key exchanges).
```