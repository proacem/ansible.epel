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

None

## Dependencies

None

## Example Playbook

```yml
    - hosts: all
      roles:
        - sbaerlocher.epel
```

## Changelog

### 1.2

* update year

### 1.1

* update

### 1.0

* Initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher
