# Ubuntu02

## Overview

Ubuntu02 is the container and automation server for the Atlas Infrastructure Foundation lab.

---

## Host Information

Hostname:
ubuntu02

Operating System:
Ubuntu Server 24.04

IP Address:
10.10.20.21

Subnet Mask:
255.255.255.0

Gateway:
10.10.20.1

DNS:
10.10.20.10

Network:
SERVERS (10.10.20.0/24)

---

## Purpose

Ubuntu02 will host:

- Docker
- Portainer
- Ansible
- Monitoring Services
- Future Kubernetes Components

---

## Installed Packages

- git
- curl
- wget
- vim
- htop
- tree
- dnsutils
- net-tools
- unzip

---

## Connectivity Validation

### pfSense

10.10.20.1

### Domain Controller

10.10.20.10

### Ubuntu01

10.10.20.20

### Internet

8.8.8.8

---

## Screenshots

### Network Configuration

../screenshots/linux/ubuntu02-network.png

### Routing Table

../screenshots/linux/ubuntu02-route.png

### DNS Resolution

../screenshots/linux/ubuntu02-dns.png
