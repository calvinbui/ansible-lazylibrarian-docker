[![Build Status](https://travis-ci.com/calvinbui/ansible-lazylibrarian-docker.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-lazylibrarian-docker)
![GitHub release](https://img.shields.io/github/release/calvinbui/ansible-lazylibrarian-docker.svg)
![Ansible Quality Score](https://img.shields.io/ansible/quality/40535.svg)
![Ansible Role](https://img.shields.io/ansible/role/d/40535.svg)

# Ansible LazyLibrarian

LazyLibrarian in Docker

##  Requirements

N/A

## Role Variables

`lazylibrarian_name`: Name of container

`lazylibrarian_image`: Docker image to  use

`lazylibrarian_ports`: List of ports to expose

`lazylibrarian_config_directory`: Directory to store configuration files

`lazylibrarian_books_directory`: Directory to store books

`lazylibrarian_download_directory`: Directory to store downloads

`lazylibrarian_environment_variables`: Docker environmental variables

`lazylibrarian_docker_additional_options`: [Additional parameters](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html) to add to docker container

`lazylibrarian_config`: Options to change in configuration file

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
   - role: calvinbui.ansible_lazylibrarian_docker
```

## License

GPLv3

## Author Information

http://calvin.me
