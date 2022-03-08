# Ansible Collection: serdigital64.security

## About

Ansible Roles for automating security tools provisioning.

This collection is part of the [A:Platform64](https://github.com/serdigital64/aplatform64) project for automated infrastructure-as-code management.

## Content

| role                                                                                        | purpose                                                 |
| ------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| [sec_firewall_os](https://aplatform64.readthedocs.io/en/latest/roles/sec_firewall_os)       | Manage provisioning of Operating System native Firewall |
| [sec_key_ssh](https://aplatform64.readthedocs.io/en/latest/roles/sec_key_ssh)               | Manage SSH Keys provisioning                            |
| [sec_openssh_client](https://aplatform64.readthedocs.io/en/latest/roles/sec_openssh_client) | Manage provisioning of OpenSSH client                   |
| [sec_openssh_server](https://aplatform64.readthedocs.io/en/latest/roles/sec_openssh_server) | Manage provisioning of OpenSSH server                   |

## Deployment

### Dependencies

- Ansible Collections:
  - ansible.posix
  - community.crypto
  - serdigital64.backup
  - serdigital64.system

### Installation Procedure

Manually install Ansible Collections from the Ansible Galaxy repository:

```shell
ansible-galaxy collection install --upgrade serdigital64.security
```

Automatic installation is also available by deploying [A:Platform64](https://aplatform64.readthedocs.io/en/latest/#deployment)

## Contributing

Help on implementing new features and maintaining the code base is welcomed.

Please see the [guidelines](https://aplatform64.readthedocs.io/en/latest/contributing/guidelines) for further details.

## Author

- [SerDigital64](https://serdigital64.github.io/)

## License

[GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.txt)