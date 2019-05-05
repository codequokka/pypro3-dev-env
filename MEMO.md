Testing to prodction server
---------------------------
- Add vagrant instance ssh-config
```console
$ vagrant ssh-config >> ~/.ssh/config
```

- Install ansible, testinfra into venv
```console
$ pipenv install -d
$ pipenv shell
```

- Set invetory file then execute tests
```console
(.venv)$ export MOLECULE_INVENTORY_FILE=.vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory
(.venv)$ pytest --hosts='ssh://default'
```
