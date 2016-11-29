```bash
ansible-playbook \
  -i ansible/inventories/development/hosts.ini \
  -u vagrant \
  --private-key=.vagrant/machines/default/virtualbox/private_key \
  ansible/playbook.yml
```
