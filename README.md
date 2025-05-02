### About: 
Spring cloud config server implementation

- Setup Vault:
You can either use the cloud-based solution or set-up your self-hosted Vault with docker:
```bash
docker run -d --name vault -p 8200:8200  -e 'VAULT_DEV_ROOT_TOKEN_ID=root' -e 'VAULT_DEV_LISTEN_ADDRESS=0.0.0.0:8200' hashicorp/vault:latest
```