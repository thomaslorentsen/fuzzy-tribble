```bash
ansible-playbook \
  -i ansible/inventories/development/hosts.ini \
  -u vagrant \
  --private-key=.vagrant/machines/default/virtualbox/private_key \
  ansible/playbook.yml
```

```
ansible-playbook \
  -i ansible/inventories/development/fe.ini \
  -u vagrant \
  --private-key=../giffgaff-fe/.vagrant/machines/default/virtualbox/private_key \
  ansible/playbook-upgrade-apache.yml
```

```
yum info installed httpd
```
