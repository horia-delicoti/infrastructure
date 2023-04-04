# My personal infrastructure Playbooks

## Prerequisites

- Install [Task](https://taskfile.dev/)

```sh
brew install go-task
```

- Run command to install the environment and all dependencies

```sh
task init
```

## Getting started

```sh
ansible-playbook docker_server.yml -u <user> -K
```

## Links

- [Initial server setup with Ubuntu 22.04][server_setup_ubuntu]

<!-- Link labels: -->

[server_setup_ubuntu]: https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-22-04