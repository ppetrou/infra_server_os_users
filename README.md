Role Name
=========

A simple role to create users and groups in Linux

Requirements
------------

user and groups module requirements based on :

* https://docs.ansible.com/ansible/latest/modules/user_module.html
* https://docs.ansible.com/ansible/latest/modules/group_module.html

Role Variables
--------------

```

Variable                                Level       Description                                                         

os_users                                Default     The os users and groups to create

```


Dependencies
------------

NA

Example Playbook
----------------

```
---
- hosts: target_server
  become: yes
  roles:
    - { role: infra_server_os_users } 
```   

License
-------

BSD

Author Information
------------------

Petros Petrou - ppetrou@gmail.com
