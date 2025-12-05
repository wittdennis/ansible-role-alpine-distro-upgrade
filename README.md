# alpine_distro_upgrade

Role that upgrades Alpine Linux to a new release branch

## Requirements

- Alpine Linux system obviously
- community.general collection

## Role Variables

```yaml
alpine_distro_upgrade_version: v3.23 # The alpine version to upgrade to
```

## Example Playbook

```yaml
- name: Upgrade Alpine machines
  hosts: servers
  roles:
    - {
        role: wittdennis.alpine_distro_upgrade,
        alpine_distro_upgrade_version: "v3.23",
      }
```

## License

MIT
