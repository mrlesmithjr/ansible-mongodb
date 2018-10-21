# ansible-mongodb

<!-- TOC -->

- [ansible-mongodb](#ansible-mongodb)
  - [Requirements](#requirements)
  - [Role Variables](#role-variables)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

<!-- /TOC -->

An [Ansible](https://www.ansible.com) role to install [MongoDB](https://www.mongodb.org/)

## Requirements

If setting up replication, ensure that DNS works between hosts or
update /etc/hosts appropriately.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
---
- hosts: test-nodes
  become: true
  vars:
    pri_domain_name: 'test.vagrant.local'
  roles:
    - role: ansible-mongodb
  tasks:
```

## License

MIT

## Author Information

Larry Smith Jr.

- [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
