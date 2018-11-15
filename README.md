[![Build Status](https://travis-ci.org/onigra/ansible-role-ruby-ignore-rbenv.svg?branch=master)](https://travis-ci.org/onigra/ansible-role-ruby-ignore-rbenv)

Ansible ruby-ignore-rbenv
=========

Install ruby system wide from ruby-build igonore rbenv

Requirements
------------

No

Role Variables
--------------

```yml
ruby_ignore_rbenv:
  ruby_version: 2.5.3
  ruby_build_repo: https://github.com/rbenv/ruby-build.git
  install_path: /usr/local/lib
```

Dependencies
------------

No

Example Playbook
----------------

```yml
---
- hosts: all
  become: yes
  become_method: sudo
  roles:
    - { role: onigra.ruby-ignore-rbenv }
```

and see [example directory](https://github.com/onigra/ansible-role-ruby-ignore-rbenv/tree/master/examples)

License
-------

MIT

Author Information
------------------

Onigra

