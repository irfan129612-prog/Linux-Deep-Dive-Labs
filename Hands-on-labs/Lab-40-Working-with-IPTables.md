# Lab 40 - Working with IPTables

## Overview

This lab explores packet filtering and firewall rule management using IPTables.

## Commands Practiced

```bash
sudo iptables -L
sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT
sudo iptables-save > /etc/iptables/rules.v4
```

## Key Concepts

- Packet Filtering
- Firewall Rules
- Network Security
- Traffic Control

## Practical Outcome

Successfully configured firewall rules using IPTables.
