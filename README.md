## Role Name
imbicile.duf
imbicile.gotop

## Role Information
Install
https://github.com/muesli/duf
https://github.com/xxxserxxx/gotop

## Example Playbook
```yml
---
- hosts:
    - all
  roles:
    - { role: imbicile.duf,   become: true }
    - { role: imbicile.gotop, become: true }
```
## Example Local Playbook
```yml
---
- hosts: 127.0.0.1
  connection: local
  roles:
    - { role: imbicile.duf,   become: true }
    - { role: imbicile.gotop, become: true }
```
## Run
```sh
ansible-playbook playbooks/main.yml
```


## Author Information
https://imbicile.pp.ru
