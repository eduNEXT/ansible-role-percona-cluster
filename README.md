<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [ansible-role-percona-cluster](#ansible-role-percona-cluster)
  - [Getting Started](#getting-started)
  - [Build Status](#build-status)
  - [Role Variables](#role-variables)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# ansible-role-percona-cluster

An [Ansible](https://www.ansible.com) role to install/configure [Percona-XtraDB-Cluster]

## Getting Started

```yaml
---
- name: Percona Cluster
  hosts: percona-cluster
  vars:
    ansible_master_group_name: percona-cluster-masters
  roles:
    - maycson_fonseca.ansible_role_percona_cluster
```

## Build Status

[![Build Status](https://travis-ci.org/maycson-fonseca/ansible-role-percona-cluster.svg?branch=master)](https://travis-ci.org/maycson-fonseca/ansible-role-percona-cluster)

## Role Variables

[Role Defaults](./defaults/main.yml)

## Dependencies

None

## Example Playbook

[Example Playbook](./playbook.yml)

## License

BSD

## Author Information

Maycson Fonseca

- [maycson.fonseca@gmail.com](mailto:maycson.fonseca@gmail.com)
