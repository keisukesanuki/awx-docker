awx-docker
=========

awx(docker)を構築するplaybook

Requirements
------------

- CentOS7
- ansible 2.9.2

Role Variables
--------------

- none

Dependencies
------------

- none

Usage
----------------

- targetの定義

```
vi hosts
=====================================
[target]
awx-server ansible_host=192.168.33.55
```

- 実行

```
ansible-playbook site.yml --ask-pass
```

License
-------

BSD

Author Information
------------------

- keisuke sanuki
