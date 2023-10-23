# portainer-wrap

A docker compose wrapper for portainer

### Running the app

1. Have docker installed (19.03.0+)
2. Read through the comments in the compose file
3. Run `docker volume create portainer_data`
5. Run `./proxy.sh up`

### Other Commands

- `./proxy.sh down` : Stop server
-  `./proxy.sh update` : Update server
