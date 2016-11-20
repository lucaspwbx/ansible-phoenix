## Simple ansible role for deploying a phoenix app in a ubuntu box
Database username and password must be in the following environment variables:
- DB_USERNAME
- DB_PASSWORD
Port also must be in a enviroment variable:
- PORT

```
vagrant up
ansible-playbook site.yml
```
