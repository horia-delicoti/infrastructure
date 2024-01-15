# How to install wireguard

## Check IP within server

```sh
curl -w "\n" ifconfig.me
```

## Check IP inside container

```sh
docker exec it <container_name> curl -w "\n" ifconfig.me
```

## Useful links

- [Set up Wireguard VPN in Docker on Raspberry Pi](https://blog.davidsha.me/wireguard-vpn-setup/#)
- [How to connect to a WireGuard VPN server from a Docker container](https://www.pedrolamas.com/2020/11/20/how-to-connect-to-a-wireguard-vpn-server-from-a-docker-container/)
- [How to Monitor Who’s Connected to Your WireGuard VPN](https://www.procustodibus.com/blog/2021/01/how-to-monitor-wireguard-activity/)
- [Tunnel traffic of docker containers](https://carloalbertoscola.it/2023/linux/infrastructure/how-to-tunnel-container-traffic-vpn-wireguard/)
