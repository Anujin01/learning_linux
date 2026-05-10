# Linux Fundamentals Part 3-1 - TryHackMe

**Date:** 5/09/2026

**Path:** Pre-Security

## What This Room Covered

In this room i learned how to see, manage and start on boot programs/processes inside the kernel and managing packages and maintaining logs.

### Commands I Learned

```
ps - list of running processes

ps aux - processes run by other users

systemctl - interact with systemd daemons

crontab - schedule a certain task or or actions

```

### What actually clicked 

The first process (PID 1), **systemd**, acts as the 'parent' of all other services. We can monitor this family tree 
using **ps aux**. If a task is too heavy for the foreground, we move it to the background using ```& or bg```. For long-term
automation, we use **crontab** for schedules and **systemctl** to ensure services start automatically on boot."
