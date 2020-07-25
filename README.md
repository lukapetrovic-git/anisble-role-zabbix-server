# Ansible role for Zabbix server
Ansible role for Zabbix-server

# Requirements
No special requirements, note that this role requires root access, so either run with a global become: yes, or invoke the role in your playbook.

# Role Variables 
Role Variables listed below
```
zabbix_domen: [Your Zabbix domain]
zabbix_timezone: [timezone for your Zabbix server]
zabbix_database_user:
zabbix_database_name:
nginx_listen_port: [listen port for Nginx - default 80]
```
