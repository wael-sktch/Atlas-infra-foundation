# Linux Server Inventory

## Overview

This document tracks all Linux systems deployed in the Atlas Infrastructure Foundation lab.

---

## Ubuntu01

### Purpose

Infrastructure Services Server

### Host Information

- Hostname: ubuntu01
- IP Address: 10.10.20.20
- Operating System: Ubuntu Server 24.04
- Network: SERVERS (10.10.20.0/24)

### Services

- Git
- Curl
- Wget
- DNS Tools
- System Administration Tools

### Status

✅ Online

---

## Ubuntu02

### Purpose

Container and Automation Server

### Host Information

- Hostname: ubuntu02
- IP Address: 10.10.20.21
- Operating System: Ubuntu Server 24.04
- Network: SERVERS (10.10.20.0/24)

### Planned Services

- Docker
- Portainer
- Ansible
- Monitoring

### Status

✅ Online

---

## Network Information

| Hostname | IP Address | Purpose |
|-----------|-----------|-----------|
| ubuntu01 | 10.10.20.20 | Infrastructure Services |
| ubuntu02 | 10.10.20.21 | Containers & Automation |

---

## DNS Configuration

DNS Server:
10.10.20.10

Domain:
atlas.local

Gateway:
10.10.20.1

