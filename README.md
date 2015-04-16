# Blueprint

Configuration for my machine

# Instructions

1. Install ansible
2. Get dependencies:
```sh
$ ansible-galaxy install hnakamur.osx-defaults
```
3. Execute the following ```ansible-playbook``` command:
```sh
$ ansible-playbook -i "local," blueprint.yml
```
