# ansible-openssl-pki

Ansible Role to create a CA Certificate + Certificates per Node. Certificate generation is delegated to localhost in the
Playbook Folder /pki


## Simple Example Playbook

```
- hosts: all
  roles:
   - openssl-pki
```
