# Configuring Privileged EXEC Mode Security on Cisco Switches

## Description
This project demonstrates how to secure Privileged EXEC mode on Cisco switches using the `enable secret` command. It’s part of basic network device hardening to prevent unauthorized configuration changes.

## Prerequisites
- Cisco Packet Tracer or physical Cisco switch
- Basic knowledge of Cisco CLI
- CCNA-level networking fundamentals

## Commands Used
enable
configure terminal
enable secret <password>
exit
write



## Steps
1. Enter Privileged EXEC mode (`enable`)
2. Go to Global Configuration mode (`configure terminal`)
3. Set encrypted password (`enable secret <password>`)
4. Exit configuration mode (`exit`)
5. Save configuration (`write`)

## Outcome
After completion, Privileged EXEC mode is secured with an encrypted password, protecting the switch from unauthorized access.

