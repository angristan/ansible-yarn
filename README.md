# Ansible role for Yarn

This is a simple role that will install Yarn on Debian/Ubuntu from the [official APT repo](https://yarnpkg.com/en/docs/install#debian-stable).

## Sample playbook

```yaml
---

- hosts: myhost
  roles:
    - name: yarn
      tags: yarn
```
