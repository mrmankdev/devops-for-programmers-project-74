### Devops For Programmers 1st Project

[![Actions Status](https://github.com/mrmankdev/devops-for-programmers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/mrmankdev/devops-for-programmers-project-74/actions)
[![Build status](https://github.com/mrmankdev/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg?event=push)](https://github.com/mrmankdev/devops-for-programmers-project-74/actions)

## Deliverables

Docker Image: https://hub.docker.com/repository/docker/mrmankdev/devops-for-programmers-app


### Configuration

```env
DATABASE_NAME=posgres
DATABASE_USERNAME=posgres
DATABASE_PASSWORD=posgres
```

## Development

### Requirements
- Make
- Docker

### Commands

```bash
make compose-setup
make compose-dev
make compose-test
```


