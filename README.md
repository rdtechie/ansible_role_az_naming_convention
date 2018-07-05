# Ansible Role: az_naming_convention

Creates names for Azure resources.

## Requirements

None

## Role Variables

Variables can be set in the vars/vars.yml file

## Dependencies

None

## Example Playbook - Creates Names for Azure Reources

```yaml
---
- name: Create Name for a Azure Resource Group
  hosts: localhost
  connection: local
  gather_facts: false
  vars_files:
    - ./vars/vars.yml
  roles:
    - { role: rdtechie.ansible_role_naming_convention }
...
```

## License

MIT

## Author Information

This role was created in 2018 by [Richard Diphoorn](https://www.richarddiphoorn.com/).
