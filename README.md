# 🐧 Linux Learning & Reference

A growing collection of **Linux learning resources, command references, notes, cheat sheets, and documentation**.

This repository is intended to serve as a personal Linux knowledge base that can be expanded over time with additional `.txt`, `.pdf`, `.html`, Markdown files, notes, examples, and other useful resources.

---

## 📚 Repository Contents

Currently, this repository contains:

### 1. Linux Fundamentals

**File:** `linuxfun.pdf`

A comprehensive Linux fundamentals resource covering topics such as:

* Linux history and distributions
* Linux installation
* Command-line fundamentals
* Man pages
* Working with files and directories
* Linux filesystem hierarchy
* Shell commands and arguments
* Shell variables
* Shell history
* File globbing
* Pipes and I/O redirection
* Linux filters
* Regular expressions
* `vi` / `vim`
* Bash scripting
* Loops and conditional statements
* Script parameters
* Users and user management
* Groups
* File permissions
* ACLs
* Hard links and symbolic links
* System administration fundamentals

The material is designed around learning Linux through practical command-line usage and hands-on practice.

---

### 2. Ubuntu CLI Cheat Sheet

**File:** `ubuntu_cli_cheat_sheet_2025.pdf`

A quick-reference guide containing commonly used Ubuntu/Linux commands, including:

* System information
* System monitoring
* Process management
* Services and `systemctl`
* Cron jobs
* File and directory management
* File permissions and ownership
* `find` and `grep`
* File compression
* Text processing
* APT package management
* Snap package management
* Users and groups
* Networking
* Netplan
* UFW firewall
* SSH and SCP
* LXD containers and virtual machines
* Ubuntu Pro

---

## 🗂️ Repository Structure

The repository will grow as more Linux resources are added.

```text
linux/
│
├── README.md
│
├── linuxfun.pdf
├── ubuntu_cli_cheat_sheet_2025.pdf
│
├── notes/
│   ├── linux_notes.txt
│   ├── shell_notes.txt
│   └── networking_notes.txt
│
├── cheatsheets/
│   ├── linux_commands.txt
│   ├── bash_cheatsheet.txt
│   └── git_linux_commands.txt
│
├── tutorials/
│   ├── linux_permissions.html
│   ├── bash_scripting.html
│   └── networking.html
│
└── resources/
    └── additional-resources.pdf
```

> **Note:** The folders above are examples. Add or reorganize them as the repository grows.

---

## 🎯 Purpose

The main goals of this repository are to:

* 📖 Learn Linux from fundamentals to advanced topics
* 💻 Practice Linux commands
* 🐚 Learn Bash and shell scripting
* 🔐 Understand Linux permissions and security
* 👤 Learn user and group management
* 🌐 Learn Linux networking
* 📦 Understand package management
* 🖥️ Learn system administration
* 🐳 Explore containers and virtualization
* ⚡ Maintain quick-reference cheat sheets
* 📝 Keep useful Linux notes in one place

---

## 🧭 Learning Areas

As the repository grows, resources will be organized around areas such as:

| Area                      | Topics                                      |
| ------------------------- | ------------------------------------------- |
| 🐧 Linux Fundamentals     | Linux basics, distributions, filesystem     |
| 📁 File Management        | `ls`, `cp`, `mv`, `rm`, `find`              |
| 🐚 Shell                  | Bash, shell variables, history, globbing    |
| 🔀 Pipes & Filters        | Pipes, redirection, `grep`, `sed`, `awk`    |
| 📜 Scripting              | Bash scripts, loops, conditions, parameters |
| 👤 Users & Groups         | User creation, groups, passwords            |
| 🔐 Security               | Permissions, ACLs, ownership, links         |
| 🌐 Networking             | IP, interfaces, SSH, networking tools       |
| 📦 Packages               | APT, Snap and package management            |
| ⚙️ Services               | `systemctl`, `journalctl`, services         |
| 🖥️ System Administration | Processes, storage, system information      |
| 📦 Containers             | LXD and container management                |
| 📝 Notes                  | Personal notes and practical examples       |
| 📚 References             | PDFs, cheat sheets, HTML resources          |

---

## 🔧 Common Commands

Some of the frequently referenced commands in this repository include:

```bash
# System information
uname -a
hostnamectl
lscpu

# Files and directories
ls
pwd
cd
mkdir
touch
cp
mv
rm

# File permissions
chmod
chown

# Search
find
grep

# Text processing
cat
less
head
tail
awk

# Package management
sudo apt update
sudo apt upgrade
sudo apt install <package>

# Networking
ip addr show
ping <host>
ss -l

# Services
sudo systemctl status <service>
sudo systemctl start <service>
sudo systemctl stop <service>

# SSH
ssh <user@host>
scp <source> <user@host>:<destination>
```

The repository's Ubuntu cheat sheet also includes commands for firewall management, Netplan, Snap, LXD, and Ubuntu Pro.

---

## 📌 Adding New Resources

This repository is intentionally designed to be expandable.

You can add:

* `.txt` — quick notes and command references
* `.pdf` — books, guides, documentation and cheat sheets
* `.html` — tutorials and web-based documentation
* `.md` — structured notes and learning guides
* `.sh` — Bash scripts and examples
* Other useful Linux-related resources

When adding a new resource, use a descriptive filename so it is easy to identify later.

### Example

```text
linux/
├── README.md
├── linuxfun.pdf
├── ubuntu_cli_cheat_sheet_2025.pdf
├── bash_commands.txt
├── linux_networking.pdf
├── permissions.md
└── systemd.html
```

---

## 🚀 How to Use This Repository

If you are learning Linux, a good progression is:

```text
Linux Fundamentals
        ↓
Command Line
        ↓
Files & Directories
        ↓
Shell & Bash
        ↓
Users & Groups
        ↓
Permissions & Security
        ↓
Networking
        ↓
Package Management
        ↓
Services & System Administration
        ↓
Containers & Advanced Topics
```

Use the PDFs and reference files for learning, then practice the commands directly on a Linux system.

---

## 📝 Personal Notes

This repository can also be used as a personal knowledge base.

When learning a new Linux concept:

1. Study the concept.
2. Practice the commands.
3. Add useful commands or explanations to a `.txt` or `.md` file.
4. Add relevant documentation or reference material.
5. Keep improving the repository over time.

---

## 📈 Repository Status

**Status:** 🚧 Continuously Growing

More Linux resources, notes, cheat sheets, tutorials, and practical examples will be added over time.

---

## 📄 License & Attribution

Resources contained in this repository may have their own licenses and attribution requirements.

Before redistributing or modifying third-party resources, check the license associated with the individual file.

For example, the `Linux Fundamentals` material identifies itself as being distributed under the **GNU Free Documentation License (GFDL) 1.3 or later**.
