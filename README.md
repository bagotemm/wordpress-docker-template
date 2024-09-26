# Requirements
Docker

# Launching

Launch project and database with Docker

 ```
docker compose up -d
 ```

## First launching special instructions

During first launch, you need to wait until all files are being copied to ```/var/www/html``` in container. 

This container's directory is synced with your local ```src``` directory.

Once is done, not only could you browser on http://localhost:8080 but you could also delete ```src/delete-me``` file.

## Database informations
- Host : localhost (on local) / db (in docker compose network)
- Port : 3306
- User : wp
- Pass : wp
- Schema : wp

