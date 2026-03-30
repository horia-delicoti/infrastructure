# Install n8n with Docker Compose

## Command

Commands for the n8n deployment using Ansible playbook:

```sh
ansible-playbook n8n.yml --extra-vars "n8n_deployment=install" --limit <target_host> # to install the deployment
ansible-playbook n8n.yml --extra-vars "n8n_deployment=remove" --limit <target_host> # to remove the deployment
```

## Links

- [n8n Website](https://n8n.io/) ([Docker Hub](https://hub.docker.com/r/n8nio/n8n)) ([GitHub](https://github.com/n8n-io/n8n)) ([Documentation](https://docs.n8n.io/))
