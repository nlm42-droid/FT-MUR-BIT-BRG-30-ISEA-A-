# Session 1b - Linux Services, File Permissions and File Analysis

## Lab Objective

The objective of this lab was to explore Linux system administration, networking services, user and group permissions, secure file transfers, file compression, and advanced file searching techniques. This session provided practical experience with Apache, SSH, UFW firewall, Linux permissions, user management, and command-line file analysis tools.

# Part 1b-1 Linux Services, SSH, Firewalls and Compression

## Deliverable 1 - Apache Web Server Installed

Apache web server was installed and tested successfully using localhost.

![Apache Installation](screenshots/1b-apache-installed.png)

![Apache Default Page](screenshots/1b-apache-default.png)

---

## Deliverable 2 - Modified index.html Page

The Apache default webpage was modified with custom content and verified through a web browser.

![Custom Index Page](screenshots/1b-modified-index.png)

---

## Deliverable 3 - IP Address Identified

The local IP address was identified using the ip a command and used for networking activities.

![IP Address](screenshots/1b-ip-address.png)

---

## Deliverable 4 - Nmap Port Scan

Open ports and running services were identified using Nmap.

![Nmap Scan](screenshots/1b-nmap-scan.png)

---

## Deliverable 5 - Firewall Configuration

UFW firewall was enabled and configured to allow web traffic on port 80.

![Firewall Status](screenshots/1b-firewall.png)

---

## Deliverable 6 - SSH Enabled and Tested

SSH service was installed and tested successfully.

![SSH Test](screenshots/1b-ssh.png)

---

## Deliverable 7 - New User Created

A new Linux user account was created and verified.

![User Created](screenshots/1b-user-created.png)

---

## Deliverable 8 - Compression and Decompression

Files were archived and compressed using tar and bzip2.

![Compression](screenshots/1b-compression.png)

---

## Deliverable 9 - SCP File Transfer

Files were transferred securely using SCP.

![SCP Transfer](screenshots/1b-scp-transfer.png)

---

## Deliverable 10 - Hosts File Modified

The hosts file was edited and a custom hostname was tested.

![Hosts File](screenshots/1b-host-file.png)

---

## Deliverable 11 - DNS Lookup and Whois

Domain information was investigated using nslookup and whois.

![DNS Lookup](screenshots/1b-nslookup&whois.png)

---

## Deliverable 12 - Public vs Private IP

Public and private IP addresses were compared and analysed.

![Public vs Private IP](screenshots/1b-public&private_IP.png)

---

## Deliverable 13 - Hardware Information

System hardware information was obtained using Linux commands.

![Hardware Information](screenshots/1b-hardwareinfo.png)

![CPU Information](screenshots/1b-cpuinfo.png)

---

## Deliverable 14 - Output Redirection

Command output was redirected to a file and reviewed.

![Output Redirection](screenshots/1b-redirect-output.png)

---


# Part 1b-2 Linux File Permissions and Group Access Control

## Deliverable 1 - Three Users Created

Three users (alice, bob and mallory) were created and verified.

![Users Created](screenshots/1b2-01-users-created.png)

---

## Deliverable 2 - Group Created and Configured

A shared group was created and users were assigned appropriately.

![Group Created](screenshots/1b2-02-groupadd.png)

![Output](screenshots/1b2-02-output.png)

---

## Deliverable 3 - Shared Directory Created

A shared directory was created and ownership configured.

![Shared Directory](screenshots/1b2-03-shared-directory.png)

---

## Deliverable 4 - Ten Files Created

Ten files were created within the shared directory.

![Shared Files](screenshots/1b2-04-shared-directory.png)

---

## Deliverable 5 - Permissions Assigned

Permissions were configured using chmod, chown and chgrp.

![Permissions](screenshots/1b2-05-permissions.png)

---

## Deliverable 6 - User Access Verified

Access permissions were tested using alice, bob and mallory accounts.

![User Access Test](screenshots/1b2-06-user-access.png)

---

## Deliverable 7 - Recursive Permission Commands

Recursive permission changes were applied successfully.

![Permissions](screenshots/1b2-07-recursive.png)

---

## Deliverable 8 - Mallory Added to Sudo Group

Mallory was granted sudo privileges.

![Mallory Sudo Group](screenshots/1b2-08-sudo-user.png)

---

## Deliverable 9 - Sudo Access Tested

Mallory successfully executed privileged commands.

![Sudo Test](screenshots/1b2-09-sudo-access.png)

---

## Deliverable 10 - Clean-up Completed

The shared directory and files were removed.

![Cleanup](screenshots/1b2-10-deleted.png)

---

# Part 1b-3 File Search, Analysis and Archiving

## Deliverable 1 - Archive Extraction

The Gutenberg archive was successfully extracted.

![Archive Extraction](1b-archive-extraction.png)

## Deliverable 2 - File Listing

Extracted files were listed and verified.

![File Listing](1b-file-listing.png)

## Deliverable 3 - Filename Search

Files were searched by filename and extension.

![Filename Search](1b-filename-search.png)

## Deliverable 4 - Text Search Using Grep

Text searches were performed using grep.

![Grep Search](1b-grep-search.png)

## Deliverable 5 - Context Search

Contextual text searching was performed.

![Context Search](1b-context-search.png)

## Deliverable 6 - Date-Based Search

Files were searched and sorted by modification date.

![Date Search](1b-date-search.png)

## Deliverable 7 - Size-Based Search

Files were searched by exact size.

![Size Search](1b-size-search.png)

## Deliverable 8 - Largest Files Found

The largest files in the archive were identified.

![Largest Files](1b-largest-files.png)

## Deliverable 9 - Word Frequency Analysis

Word frequency analysis was performed using sed, sort and uniq.

![Word Frequency](1b-word-frequency.png)

## Deliverable 10 - Answers to Analytical Questions

All required analytical questions were answered.

![Answers File](1b-answers-file.png)

## Summary

This session provided practical experience with Linux server administration, networking, file permissions, user management, secure remote access, file compression, archive management, and advanced command-line search tools. The activities demonstrated how Linux can be used to manage services, secure resources, and analyse large collections of files efficiently.
