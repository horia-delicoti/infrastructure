# My personal infrastructure Playbooks

## Table of Contents

-----------------

* [🔧 Prerequisites](#prerequisites)
* [💄 Getting started](#getting-started)
* [📑 License](#license)
* [↕️  Useful Links](#links)

## Prerequisites

* Install [Task](https://taskfile.dev/)

```sh
brew install go-task
```

* Run command to install the environment and all dependencies

```sh
task init
```

## Getting started

```sh
ansible-playbook docker_server.yml -u <user> -K
```

## License

MIT

## Links

* [Initial server setup with Ubuntu 22.04][server_setup_ubuntu]
* [HTPC download box][htpc-download-box]
* [Ansible role prometheus][ansible-role-prometheus]

<!-- Link labels: -->

[server_setup_ubuntu]: https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-22-04
[htpc-download-box]: https://github.com/sebgl/htpc-download-box
[ansible-role-prometheus]: https://github.com/ome/ansible-role-prometheus
[install_prometheus_rpi]: https://pimylifeup.com/raspberry-pi-prometheus/
