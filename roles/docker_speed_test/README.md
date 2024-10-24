# Speed Test Tracker

- [Docs Speed Test Tracker](https://docs.speedtest-tracker.dev/getting-started/database-drivers)
- [Docker Speed Test Tracker](https://docs.linuxserver.io/images/docker-speedtest-tracker/)

## Getting Started

Get APP Key from [speedtest-tracker.dev](https://speedtest-tracker.dev/)

```sh
ansible-playbook docker_speed_test.yml --extra-vars "speed_test_deployment=install speed_test_app_key=<app_key>" --limit <server>
```
