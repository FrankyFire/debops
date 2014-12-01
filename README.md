## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) debops

[![Travis CI](http://img.shields.io/travis/debops/ansible-debops.svg?style=flat)](http://travis-ci.org/debops/ansible-debops) [![test-suite](http://img.shields.io/badge/test--suite-ansible--debops-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-debops/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.debops-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1557)

Install DebOps scripts, and optionally automatically download DebOps
playbooks and roles and install them system-wide in `/usr/local`. This role
can be used to easily setup a remote Ansible Controller using Ansible.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.debops

### Documentation

More information about `debops.debops` can be found in the
[official debops.debops documentation](http://docs.debops.org/en/latest/ansible/roles/debops.debops.html).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`debops` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
