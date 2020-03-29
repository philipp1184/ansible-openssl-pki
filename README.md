# ansible-openssl-pki

Ansible Role to create a CA Certificate + Certificates per Node. Certificate generation is delegated to localhost. Certifcates are placed in Folder /pki of your Playbook. 


## Simple Example Playbook

```
- hosts: all
  roles:
   - openssl-pki
```
