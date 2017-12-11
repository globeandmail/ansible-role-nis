ansible-role-nis
======

This role is intended to install NIS, and manage yp.conf


Variables (optional)
------

```
ansible_role_nis_cfg_path: /path/to/group_files/nis/yp.conf
```


Notes
------

If ansible_role_nis_cfg_path is undefined, the existing file will be left untouched.

At the time of this writing, only Ubuntu is supported.
