daixijun.cron
=========

配置Crontab

Requirements
------------

* ansible 2.7

Role Variables
--------------

[Role变量](defaults/main.yaml)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
      - { role: daixijun.cron, name: "uptime", job: "uptime", minute: "*/30" }
```

License
-------

BSD

Author Information
------------------

Xijun Dai <daixijun1990@gmail.com>
