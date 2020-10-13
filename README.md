# ansible-role-automation-user

An Ansible Role that provisions a secure automation user for a system

## Requirements

None.

## Role variables
`automation_user: ansible`

Add your public key to the `files/public_keys` file

Note: It is possible to add multiple keys into that file as well, on separate lines.
Behaviour is the same as with authorized_keys

### DISCLAIMER: This role has to be run with root privileges (--ask-become-pass)

#### License
MIT
