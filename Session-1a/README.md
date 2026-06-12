# Session 1a - Virtualisation, Ubuntu Desktop and Command Line Familiarisation

## Lab Objective

The objective of this lab was to install and configure Ubuntu Linux in a virtual machine environment and become familiar with both the Ubuntu graphical desktop environment and command-line interface. The lab also introduced basic networking, file management, system information, user management, and software installation techniques.

# Part 1a-1 Virtualisation and Linux Setup

## Deliverable 1 - Virtualisation Software Installed

VMware Workstation was installed and configured to host Ubuntu Linux in a virtual machine environment.

![VMware Installed](screenshots/vmware-installed.png)

## Deliverable 2 - Ubuntu ISO Downloaded

The Ubuntu ISO image was downloaded from the official Ubuntu website and used as installation media.

![Ubuntu ISO](screenshots/ubuntu-iso.png)

## Deliverable 3 - New Virtual Machine Created

A new Ubuntu virtual machine was created with at least 2048 MB RAM and the ISO image mounted as a virtual CD drive.

![VM Settings](screenshots/vm-settings.png)

## Deliverable 4 - Ubuntu Installation Completed

Ubuntu Linux was successfully installed and rebooted inside the virtual machine.

![Ubuntu Desktop](screenshots/ubuntu-desktop.png)

## Deliverable 5 - Networking Mode Configured

NAT networking was configured to provide internet access from the virtual machine.

![Network Settings](screenshots/network-settings.png)

## Deliverable 6 - Ubuntu Running Successfully

Ubuntu was verified to be fully operational through the graphical desktop and terminal interface.

![Ubuntu Running](screenshots/ubuntu-running.png)

# Part 1a-2 Ubuntu Desktop and Command Line Familiarisation

## GUI Familiarisation

Ubuntu desktop applications including Firefox, LibreOffice, File Manager and Ubuntu Software Centre were explored.

![Firefox](screenshots/firefox.png)

![LibreOffice](screenshots/libreoffice.png)

![File Manager](screenshots/file-manager.png)

## Terminal Commands

The following commands were executed to explore the Linux environment:

```bash
ps -e
top
ls
ls -la
ls -alt
```

![Terminal Commands](screenshots/terminal-commands.png)

## File Operations

Files were created, edited, copied, moved and deleted using Linux command-line tools.

```bash
touch file1.txt
nano file1.txt
cp file1.txt copy.txt
mv copy.txt moved.txt
rm moved.txt
ls -lah
```

![File Operations](screenshots/file-operations.png)

## System Information

System information was obtained using:

```bash
uname -a
lsb_release -a
hostnamectl
less /proc/cpuinfo
```

![System Information](screenshots/system-information.png)

![Cpu Info](screenshots/cpu-info.png)

## User Privilege Experiment

Administrative privileges were tested using:

```bash
whoami
sudo whoami
```

The purpose of sudo and the role of the root user were investigated.

![User Privileges](screenshots/user-privileges.png)

## Networking Tests

Network connectivity was tested using:

```bash
ip a
ping 8.8.8.8
```

![Networking](screenshots/networking.png)

## DNS and Hosts File

The /etc/hosts file was edited and DNS lookups were performed using:

```bash
nslookup google.com
whois google.com
```

![DNS Lookup](screenshots/dns-lookup.png)

## Hardware Information

Hardware information was collected using:

```bash
lsusb
lspci
less /proc/cpuinfo
```

![Hardware Information](screenshots/hardware-info.png)

## Software Installation

Software installation methods explored included:

* Ubuntu Software Centre

![Ubuntu Software Centre](screenshots/software-centre.png)

* APT Package Manager

![APT Package Manager](screenshots/apt-install.png)

* Software as a Service (SaaS)

![SaaS](screenshots/saas.png)

## Source Code Compilation

A simple C program was compiled using GCC and executed successfully.

```bash
gcc hello_world.c -o hello_world_executable
./hello_world_executable
```

![Compilation](screenshots/compilation.png)

## Summary

This lab provided practical experience with virtualization, Linux installation, Ubuntu desktop navigation, command-line operation, networking, software installation, user management and basic software compilation.
