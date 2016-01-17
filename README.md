# Ansible Role: EPEL Repository

## Description

Installs the EPEL repository (Extra Packages for Enterprise Linux) for RHEL/CentOS.

## Installation

```
$ ansible-galaxy install sbaerlocher.epel
```

## Requirements

This role only is needed/runs on RHEL and its derivatives.

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| ```epel_repo_url```| ```"https://dl.fedoraproject.org/pub/epel/epel-release-latest-{{ ansible_distribution_major_version }}.noarch.rpm"``` | url of epel |
| ```epel_repo_gpg_key_url``` | ``` "/etc/pki/rpm-gpg/RPM-GPG-KEY-EPEL-{{ ansible_distribution_major_version }}"``` | key |

## Dependencies

None

## Example Playbook

```yml
    - hosts: all
      roles:
        - sbaerlocher.epel
```

## Changelog

### 1.0

* Initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2016, Simon Bärlocher
