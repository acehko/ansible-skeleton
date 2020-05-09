# Ansible Role: Skeleton
Ansible role used as a skeleton for creating other roles.

**Supported Platforms:**
- Arch Linux
- Debian Buster
- ...

## Requirements
None.

## Role Variables
| Variable | Default | Description               |
|:---------|:--------|:--------------------------|
| **app**  | `true`  | Whether to install `app`. |

## Dependencies
None.

## Example Playbook
```yaml
- hosts: all
  gather_facts: yes
  roles:
    - role: role_name
      app: true
```

## License
[MIT](LICENSE)

## Author Information
[Andrija Čehko](https://github.com/acehko)
