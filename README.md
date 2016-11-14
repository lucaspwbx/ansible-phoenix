## Simple ansible role for deploying a phoenix app in a ubuntu box
Database username and password must be in the following environment variables:
- DB_USERNAME
- DB_PASSWORD

```
vagrant up
ansible-playbook site.yml
```
