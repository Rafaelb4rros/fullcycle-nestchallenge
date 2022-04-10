<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Description

NestJS challenge from FullCycle immersion.

The challenge is to build a Simple NestJS API that is served with docker.

## Installation

```bash
$ run git clone https://github.com/Rafaelb4rros/fullcycle-nestchallenge.git

$ docker-compose up
```

## Routes

- GET: "/api/transaction"
  - returns all transactions in database
- POST: /api/transaction" with params type and amount
  - create an new transactionc
