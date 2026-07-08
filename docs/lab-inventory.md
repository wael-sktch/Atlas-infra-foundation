# Lab Inventory

## Project

Atlas Infrastructure Foundation

## Purpose

Enterprise-style infrastructure lab built for learning:

- Networking
- Active Directory
- Linux Administration
- Firewall Management
- Infrastructure Documentation

---

# Network Information

## Servers Network

10.10.20.0/24

## Users Network

10.10.10.0/24

## Firewall

| Name | IP Address |
|--------|--------|
| pfSense (SERVERS) | 10.10.20.1 |
| pfSense (USERS) | 10.10.10.1 |

---

# Server Inventory

| Hostname | Role | IP Address |
|-----------|-----------|-----------|
| DC01 | Domain Controller + DNS | 10.10.20.10 |
| Ubuntu01 | Infrastructure Server | 10.10.20.20 |
| Ubuntu02 | Container Server | 10.10.20.21 |

---

# Client Inventory

| Hostname | Role |
|-----------|-----------|
| WIN11-CLIENT | Domain Joined Workstation |

---

# Active Directory

## Domain

atlas.local

## Organizational Units

- Users
- Admins
- Servers
- Workstations

---

# Services

## DNS

Server:
10.10.20.10

## DHCP

Server:
pfSense

Scope:
10.10.10.100 - 10.10.10.200

## Authentication

Active Directory Domain Services

---

# Documentation

## Firewall

- interfaces.md
- dhcp.md
- firewall-rules.md

## Active Directory

- dc01.md
- dns.md
- ou-structure.md

## Linux

- ubuntu01.md
- ubuntu02.md
- server-inventory.md
