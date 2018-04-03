```sh
ansible-galaxy install -p ./galaxy -r requirements.yml
vagrant up
ansible-playbook playbook.yml -i inventory.yml
```
