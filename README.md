# Docker

# Steps
1. Remove node_modules to avoid duplication when copying all files to docker image.

## docker files
- Production: `Dockerfile`
- development: `Dockerfile.dev`

## Docker scripts

| Script   | instruction  |
|---|---|
docker-dev   | docker build -f Dockerfile.dev  
|Map port|docjer |
