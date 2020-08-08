#### Playbook to provision a server with PostgreSQL


```
/etc/ansible/hosts

[dbserver]
172.16.8.152
```

```
~/.ansible.cfg

[defaults]
inventory = /etc/ansible/hosts
remote_user = root
ask_sudo_pass= true
```