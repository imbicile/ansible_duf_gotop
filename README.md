Role Name
=========

imbicile.duf
imbicile.gotop

Role Information
----------------
Install

https://github.com/muesli/duf

https://github.com/xxxserxxx/gotop

Example Playbook
----------------

    ---
    - hosts:
        - all
      roles:
        - { role: imbicile.duf,   become: true }
        - { role: imbicile.gotop, become: true }


Author Information
------------------

https://imbicile.pp.ru
