# Ansible Role Loki

This role installs [Loki](https://github.com/grafana/loki/).

## Requirements
None.

## Role Variables

``` yaml
loki_version: "2.3.0"

loki_config_dir: /etc/loki
loki_executable: /usr/local/bin/loki
loki_executable_options:
```

## Dependencies
None.

## Example Playbook

``` yaml
- hosts: all
  roles:
    - role: loki
```

## License

MIT
