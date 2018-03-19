Role Name
=========

This role provides all necessary tools for a linux machine to join active directory.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml).

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- name: Set up active directory for linux
  hosts: all
  become: yes
  roles:
    - role: linux-active-directory
      lad_domain_name: "my.domain.com"
      lad_ldap_server: "ldap.int.intelematics.com"
      lad_join_username: "Administrator"
      lad_join_password: "Password"
```

License
-------

MIT

Author Information
------------------

[@miaoulafrite](https://github.com/miaoulafrite)
