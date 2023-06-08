### Hexlet tests and linter status:
[![Actions Status](https://github.com/Alexcey/devops-for-programmers-project-74/workflows/hexlet-check/badge.svg)](https://github.com/Alexcey/devops-for-programmers-project-74/actions)

[![Workflow](https://github.com/Alexcey/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/Alexcey/devops-for-programmers-project-74/actions)

# Requirement

* Docker-compose v1.27.0+

## Installation

```bash
$ docker-compose run app npm install
```

## Start

```bash
$ docker-compose up
```

## Test

```bash
$ docker-compose -f docker-compose.yml up --abort-on-container-exit --exit-code-from app
```