# ansible-role-create-users

Create users, groups and import their SSH keys from github.

```
---
user_groups:
  - sudo
  - wheel
  - docker

users:
  - { name: ktz, groups: docker, sshkeys: ironicbadger.keys}
```

