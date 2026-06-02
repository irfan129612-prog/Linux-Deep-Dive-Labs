# Lab 55 - Secure File Deletion Using Shred

## Overview

This lab introduces secure file deletion techniques using the shred utility.

## Commands Practiced

```bash
echo "Sensitive Data" > sample.txt
cat sample.txt

shred -u sample.txt
shred -n 5 -u sample.txt

ls -l sample.txt
```

## Key Concepts

- Secure Deletion
- Data Protection
- File Overwriting
- Privacy

## Practical Outcome

Successfully removed files securely using shred.
