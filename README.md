# ansible-**role_name**
=========
[![Ansible Role](https://img.shields.io/ansible/role/ansible-**role_id**.svg)](https://galaxy.ansible.com/detail#/role/**role_id**)
[![Build Status](https://travis-ci.org/shrikeh/ansible-**role_name**.svg)](https://travis-ci.org/shrikeh/ansible-**role_name**)
[![GitHub Stars](https://img.shields.io/github/stars/shrikeh/ansible-**role_name**.svg)](https://github.com/shrikeh/ansible-**role_name**)

A brief description of the role goes here.

## Requirements
------------

None.

## Role Variables
--------------
#### [`**role_name**_pkg_install_latest`][**role_name**_pkg_install_latest]
Default: `no`
Controls whether to use 'present' or 'latest' for package installation.

## Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook
----------------

```YAML
---
    - hosts: servers
      roles:
         - { role: shrikeh.**role_name** }
...
```

## License
-------

[MIT][licence]

## Author Information
------------------
Contact me on Twitter @[barney_hanlon][twitter]

[**role_name**_pkg_install_latest]: https://github.com/shrikeh/ansible-**role_name**/blob/master/defaults/main.yml#L3 "Link to the variable definition in defaults.yml"
[licence]: https://raw.githubusercontent.com/shrikeh/ansible-**role_name**/master/LICENSE "Link to the license in the repository"
[twitter]: https://twitter.com/barney_hanlon "Link to my Twitter page"
