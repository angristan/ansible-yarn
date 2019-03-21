# Ansible role for Yarn

[![CircleCI](https://circleci.com/gh/angristan/ansible-yarn.svg?style=svg)](https://circleci.com/gh/angristan/ansible-yarn)

This is a simple role that will install Yarn on Debian/Ubuntu from the [official APT repo](https://yarnpkg.com/en/docs/install#debian-stable).

## Sample playbook

```yaml
---

- hosts: myhost
  roles:
    - name: yarn
      tags: yarn
```
