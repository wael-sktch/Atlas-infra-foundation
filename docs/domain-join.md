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

../screenshots/client/ipconfig.png

## DNS Validation

../screenshots/client/dns-test.png

## Domain User Verification

../screenshots/client/whoami.png

---

# Result

 DNS Working

 Domain Controller Reachable

 Active Directory Authentication Successful

 Client Successfully Joined To atlas.local
