# Alpine Apache2 with http and self-signed https endpoint
## Introduction

## Base
* hackinglab/alpine-base-hl:latest

## Specifications
* with s6 startup handling
* with dynamic user creation
* with or without known passwords for root and non-root user
* with `env` based dynamic ctf flag handling
* with `file` based dynamic ctf flag handling
* reverse proxy is serving files by apache2 in /opt/www
* backend service is serving files by apache2 in /opt/backend


