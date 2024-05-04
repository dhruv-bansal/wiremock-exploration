# Wiremock Exloration

## Description
This repo is a sample project that demonstrates the usage of wiremock

## Usage
To use the project, follow these steps:

1. Checkout this repo
2. Run following docker command
```
docker run -it --rm \
  -p 8080:8080 \
  --name wiremock \
  -v $PWD:/home/wiremock \
   wiremock/wiremock:3.5.4
```
Note. Local folder has two subfolders mappings and __files

## Structure
### REST files
- [ ] Write about .rest files and plugin needed

### Mappings files

