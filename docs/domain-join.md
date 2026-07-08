# Windows Domain Join

## Overview

This document demonstrates the successful integration of a Windows client into the Active Directory domain.

---

# Domain Information

## Domain Name

atlas.local

## Domain Controller

Hostname: DC01

IP Address: 10.10.20.10

## DNS Server

10.10.20.10

---

# Client Configuration

## Network

- Network: USERS
- Subnet: 10.10.10.0/24
- Gateway: 10.10.10.1
- DNS: 10.10.20.10

---

# Domain Join Process

## DNS Verification

The client was configured to use the Domain Controller as its primary DNS server.

Validation command:

```cmd
nslookup atlas.local
```

## Domain Join

The Windows client was joined to:

```text
atlas.local
```

using domain administrator credentials.

---

# Validation

## Verify Logged-in User

Command:

```cmd
whoami
```

Expected result:

```text
atlas\wael
```

## Verify IP Configuration

Command:

```cmd
ipconfig /all
```

Expected:

- DNS Server: 10.10.20.10
- Gateway: 10.10.10.1

---

# Screenshots

## IP Configuration

<img width="392" height="281" alt="Screenshot 2026-07-09 005654" src="https://github.com/user-attachments/assets/edda559d-19bd-4979-b7f1-636494b8ba67" />

## DNS Validation

<img width="454" height="211" alt="Screenshot 2026-07-09 010112" src="https://github.com/user-attachments/assets/c53828cb-c040-45d6-8feb-d9ef62ec3644" />

## Domain User Verification

<img width="464" height="259" alt="Screenshot 2026-07-09 005909" src="https://github.com/user-attachments/assets/fb50ed3c-99be-4cf5-8113-004de140f7a2" />

---

# Result

 DNS Working

 Domain Controller Reachable

 Active Directory Authentication Successful

 Client Successfully Joined To atlas.local
