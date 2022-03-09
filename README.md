Ansile Role: shinycannon
=========

An Ansible Role that installs [RStudio Shinycannon](https://github.com/rstudio/shinycannon) on Linux.


[![CI](https://github.com/Appsilon/ansible-shinycannon/workflows/CI/badge.svg)](https://github.com/Appsilon/ansible-shinycannon/actions/workflows/ci.yml)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-appsilon.shinycannon-blue.svg)](https://galaxy.ansible.com/appsilon/shinycannon)

Requirements
------------

None.

Role Variables
--------------

* `shinycannon_version` [default: `1.1.3-dd43f6b`]: Version to install
* `shinycannon_install` [default: `"default-jdk", "default-jre"`]: Additional packages to install

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
     - appsilon.shinycannon
```

License
-------

MIT

Author Information
------------------

[`Appsilon`](https://appsilon.com/)
