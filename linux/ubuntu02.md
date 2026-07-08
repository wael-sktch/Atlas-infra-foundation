
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

<img width="446" height="274" alt="Screenshot 2026-07-08 235123" src="https://github.com/user-attachments/assets/c0204e46-c54b-45b9-ab7d-e5bc751a2fde" />

### Routing Table

<img width="392" height="160" alt="Screenshot 2026-07-08 235214" src="https://github.com/user-attachments/assets/4dc87bb9-c47c-4902-a989-596b76721cfc" />


## Validation

### DNS Resolution

Command:

nslookup atlas.local 10.10.20.10

Result:

atlas.local resolved successfully through DC01 (10.10.20.10).

<img width="390" height="137" alt="Screenshot 2026-07-08 235314" src="https://github.com/user-attachments/assets/d6eda389-f320-4113-9234-6f61f0c7261e" />
