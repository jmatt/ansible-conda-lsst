ansible-conda-lsst
==================

[![Build Status](https://travis-ci.org/lsst-sqre/ansible-conda-lsst.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-conda-lsst)

Ansible automation to create LSST DM's Conda packages on Mac OS X.

Dependencies
------------

Tested with Ansible v2.1.1.0 on Mac OS X El Capitan.

Example
-------

To run the `site.yml` playbook which uses the brew, conda and dev playbooks:
```bash
ansible-playbook -i hosts --vault-password-file=/path/to/vault_password.txt ./site.yml
```

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-beats/blob/master/LICENSE).
