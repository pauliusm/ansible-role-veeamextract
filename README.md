Ansible role `veeamextract`
=========

Ansible role which downloads and extracts [Veeam Extract](https://helpcenter.veeam.com/docs/backup/vsphere/extract_utility.html?ver=100) utility.

Requirements
------------

Pretty modern Linux distro and internet connectivity (for download).
Tested on RHEL6-7, but others would work also.

Role Variables
--------------

Example Playbook
----------------

```
    - hosts: all
      roles:
        - role: pauliusm.veeamextract
```

Testing
-------

License
-------

BSD

Contributors
------------

- [Paulius Mažeika](https://github.com/pauliusm)
