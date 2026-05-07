# Linux Fundamentals Part 3-1 - TryHackMe

**Date:** 5/07/2026

**Path:** Pre-Security

## What This Room Covered

In this room i discovered we can edit the text and access to the file with not only **cat** command but also using **Nano**, **VIM** which is advanced text editor built into
linux OS. Not only this i learned to transfer files computer to computer and serving files from my host using python to start web server.

### Commands I Learned

`command > file` - replaces file

`command >> file` - adds to bottom

`command < file` - get input for command from a file 

`command 2> file` - save only the error messages to a file

Nano - easy to use file editor

VIM - advanced file editor 

SCP - secure copy this command allows to transfer files between computers using SSH

**Example of SCP:**

```bash

**copy a file from my machine to remote machine format**:scp filename.txt remote_username@remote_ip:/destination/filename.txt

**copy a file from remote computer we logged in**: scp remote_username@remote_ip-address:/location_of_file/filename.txt file.name.txt

```

`python3 -m http.server` - turns your computer into a quick easy web server

wget - this command allows us to download files from the web via HTTP (wget https://location) just need to know the web address


## What Actually Clicked

After learning these commands, I feel much more confident navigating the file system and transferring files remotely.
