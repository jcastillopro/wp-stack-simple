# wordpress-redis-nginx-docker-coolify
Prepared for deploying via coolify
- clone repo
- add domain names in default.conf
- check configs for your setup, commit and install (run with docker compose, or I do it with coolify docker compose deploy)
After installation should add plugins:
- w3 total cache - for setting up cache in redis
- ewww - for images optimisation, nginx is set up already