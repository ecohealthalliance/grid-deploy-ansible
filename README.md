Ansible deployment for GRID.

### Deploying to an AWS instance

Edit the inventory.ini file to add instance ip addresses you want to deploy to.
Then run a command like this:

```
ansible-playbook site.yml -i inventory.ini --vault-password-file ~/.grid_vault_password --private-key ~/.keys/grid-dev.pem
```
