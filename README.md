# Docker Store

[![GuardRails badge](https://badges.production.guardrails.io/moul/docker-store.svg)](https://www.guardrails.io)

A data store:

- push files via FTP/SFTP
- serve them via HTTP

## Installation

    docker-compose build
    docker-compose up -d

## Adding FTP users

    docker-compose run ftp new-ftp-user <username>
    <enter password twice>
