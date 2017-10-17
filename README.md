Role of installing Ruby
=========

Ruby ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* ruby_version  
Ruby version

* ruby_download_url  
Ruby source package url

* bundler_version  
Bundler version

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - { role: ruby, ruby_version: 2.3.3, ruby_download_url: 'http://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.3.tar.gz', bundler_version: 1.13.6 }
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")
