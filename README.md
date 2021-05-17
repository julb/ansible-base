# base

This role enables to install base packages on a system.

## Requirements

No requirements.

## Role Variables

| Name          | Type     | Location            | Description                                  |
| ------------- | -------- | ------------------- | -------------------------------------------- |
| base_packages | string[] | `defaults/main.yml` | The base packages to install on the system . |

By default, the `base_packages` list is populated with the given packages:

- jq
- zip
- unzip
- curl
- git
- htop
- tree
- vim
- yum-utils
- openssl

## Dependencies

No dependencies.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: julb.base }
```

## License

MIT

## Author Information

More to find on my [Github](https://github.com/julb).

## Contributing

This project is totally open source and contributors are welcome.

When you submit a PR, please ensure that the syntax has been checked.
