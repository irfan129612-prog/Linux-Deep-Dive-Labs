# Lab 43 - Swap Space Configuration

## Overview

This lab focuses on creating and configuring swap space to improve memory management.

## Commands Practiced

```bash
swapon --show
free -h
sudo fallocate -l 1G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
sudo nano /etc/fstab
```

## Key Concepts

- Swap Space
- Virtual Memory
- Memory Management
- System Performance

## Practical Outcome

Successfully configured and enabled swap space on a Linux system.
