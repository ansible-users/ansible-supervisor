
[![Ansible Role](https://img.shields.io/badge/role-cupen.supervisor-brightgreen.svg)](https://galaxy.ansible.com/cupen/supervisor/)

Supervisor
=========

Install [supervisor] by pip.

Requirements
------------

* `ansible`

Role Variables
--------------

* `version` :  version of supervisor.
* `python_dir` : The directory of python installed.


Dependencies
------------

* `python >= 2.7, <= 2.7.99`

Example Playbook
----------------

Install supervisor with python2.7 which installed in `python_dir`

```yaml
- hosts: servers
  roles:
     - { role: cupen.supervisor, version: '3.3.2', python_dir: '/usr/local/opt/python2.7.13' }
```

License
-------

WTFPL

```
DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
           Version 2, December 2004

Copyright (C) 2017 cupen <cupen@foxmail.com>

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.

   DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

0. You just DO WHAT THE FUCK YOU WANT TO.
```

Author Information
------------------

智慧与美貌的并重，英雄与侠义的化身！

<cupen@foxmail.com>

[supervisor]: http://supervisord.org/
