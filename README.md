# init

Role to prepare host to work with Ansible.

# Role Variables

```yaml
prepare_file: /var/tmp/.ansible_prepare
```

# Example Playbook

```yaml
- hosts: servers
  roles:
    - init
```

# License

WTFPL
