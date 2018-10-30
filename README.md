# ansible-mongodb

<!-- TOC -->

- [ansible-mongodb](#ansible-mongodb)
  - [Requirements](#requirements)
    - [Name Resolution](#name-resolution)
    - [Inventory](#inventory)
  - [Role Variables](#role-variables)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

<!-- /TOC -->

An [Ansible](https://www.ansible.com) role to install [MongoDB](https://www.mongodb.org/)

## Requirements

### Name Resolution

If setting up replication, ensure that DNS works between hosts or
update /etc/hosts appropriately.

Install additional roles applicable for this role:

```bash
ansible-galaxy install -r requirements.yml
```

### Inventory

The following is an example inventory for replication:

```bash
[mongodb_cluster]
mongo1.example.com
mongo2.example.com
mongo3.example.com
```

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

[playbook.yml](playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
