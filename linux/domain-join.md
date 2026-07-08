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

<img width="352" height="274" alt="Screenshot 2026-07-08 234021" src="https://github.com/user-attachments/assets/1aefa472-82ca-4400-aea1-d2aa614eab57" />


### Domain Membership

realm list

<img width="322" height="226" alt="Screenshot 2026-07-08 234107" src="https://github.com/user-attachments/assets/d042f845-9e21-4e4d-abd1-029792ea7663" />


### User Lookup

id Administrator@atlas.local

<img width="439" height="226" alt="Screenshot 2026-07-08 234151" src="https://github.com/user-attachments/assets/1b9e9b5c-5c3c-4a50-80e2-1fa949eeb330" />


### Kerberos

klist
