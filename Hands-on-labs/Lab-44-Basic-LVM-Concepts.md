# Lab 44 - Basic LVM Concepts

## Overview

This lab introduces Logical Volume Manager (LVM) and demonstrates logical volume creation and management.

## Commands Practiced

```bash
sudo lvdisplay
sudo fdisk -l
sudo pvcreate /dev/sdb
sudo vgcreate myvg /dev/sdb
sudo lvcreate -L 1G -n mylv myvg
sudo mkfs.ext4 /dev/myvg/mylv
sudo mount /dev/myvg/mylv /mnt/mylv
sudo umount /mnt/mylv
sudo lvremove /dev/myvg/mylv
sudo vgremove myvg
sudo pvremove /dev/sdb
```

## Key Concepts

- Physical Volumes
- Volume Groups
- Logical Volumes
- Flexible Storage Management

## Practical Outcome

Successfully created and managed storage using LVM.
