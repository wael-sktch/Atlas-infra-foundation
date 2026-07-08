# Ubuntu02 Active Directory Integration

## Domain

atlas.local

## Domain Controller

DC01
10.10.20.10

## Tools

- realmd
- sssd
- adcli
- kerberos

## Validation

### Domain Discovery

realm discover atlas.local

### Domain Membership

realm list

### User Lookup

id Administrator@atlas.local

### Kerberos

klist
