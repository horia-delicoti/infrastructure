# Instructions

## Claim your token from plex

```sh
https://www.plex.tv/claim/
```

```sh
ansible-playbook docker_plex.yml --extra-vars "plex_claim=claim-AAbbccc" -u <user> -K --limit <server>
```
