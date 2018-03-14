# Ansible Role: EPEL Repository

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.epel.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.epel) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-epel-blue.svg)](https://galaxy.ansible.com/sbaerlocher/epel)

## Description

Installs the EPEL repository (Extra Packages for Enterprise Linux) for RHEL/CentOS.

## Installation

```bash
ansible-galaxy install sbaerlocher.epel
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
* new style check
* support become

### 1.1

* update

### 1.0

* Initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher
