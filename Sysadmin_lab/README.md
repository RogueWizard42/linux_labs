# Linux Sysadmin Lab – 14 Hands-On Tasks

This repo documents my journey through a self-built, hands-on Linux sysadmin lab—designed to level up my skills through practical tasks, and shared for others to follow and learn from.

---

## 🎯 Why I'm Doing This

I’m doing this to learn and grow my Linux system administration skills. The best way I know how to learn is by doing—and just as importantly, by explaining what I did and why I did it. This repo reflects that approach: every task is broken down, explained in plain language, and documented with screenshots.

And let’s be honest: if I can’t explain it simply, I probably don’t understand it yet. That’s the whole point.

---

## 🛠️ Prerequisites & Tools

This lab assumes some basic comfort with Linux and the command line. You don’t need to be a wizard (yet), but you should know how to navigate directories, run commands with `sudo`, and edit config files.

**You'll need:**
- A Linux machine (this lab was built on Ubuntu 24.04)
- A hypervisor like VMware or VirtualBox
- ISO images for:
  - 2× Ubuntu Server (or similar)
  - 1× Lubuntu (for a lightweight desktop)
  - 1× Linux Mint (as a GUI-based client)
- Basic terminal and networking knowledge
- Packet Tracer (or any network diagram tool you prefer—for documenting topology)

> ⚠️ *You're welcome to use other Linux distros—or even Windows VMs—but just note that certain steps (especially networking and service setup) will differ depending on the OS.*

---

## 📚 Task Outline

This lab is structured around 14 progressive tasks, starting with a single VM and scaling to a four-VM network. Each task introduces a key Linux sysadmin skill, explained and demonstrated with real commands and screenshots.

1. **Initial Setup & CLI Basics** – Install Ubuntu Server, update the system, and get comfortable with basic commands.
2. **Package Management & Repositories** – Install/remove packages, and add a third-party repository.
3. **File System Navigation & Permissions** – Create, move, and secure files/directories using chmod and chown.
4. **User and Group Management** – Create users, groups, and assign permissions appropriately.
5. **SSH Setup for Remote Access** – Configure OpenSSH and test access from your host machine.
6. **Static IP and Network Basics** – Assign a static IP and verify connectivity.
7. **Web Server Setup (Apache)** – Install Apache and serve a simple webpage.
8. **Cron Jobs for Automation** – Write a backup script and schedule it with cron.
9. **Cloning & Expanding to a Second VM** – Clone your VM, change hostname/IP, and verify network access.
10. **NFS File Sharing** – Share directories between VMs using NFS.
11. **Desktop Admin via Lubuntu** – Add a GUI-based admin VM and connect to Server1 using `ssh -X`.
12. **LDAP Setup (Server Side)** – Install and configure OpenLDAP for centralized user management.
13. **LDAP Client Integration (Mint)** – Configure Mint VM as an LDAP client and log in with remote credentials.
14. **Monitoring & Reporting** – Install `nmon`, collect usage data, and write a summary report.

Each task has its own folder with a README and screenshots to walk through the process.

---
