<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description
# 📌 RealEstate API

A **modular, full-featured backend API** built with [NestJS](https://nestjs.com/).  
This project demonstrates how to build a **modern, scalable backend** with:
- ✅ Secure authentication (Local, JWT, Google OAuth)
- ✅ Role-based authorization using Guards & Decorators
- ✅ Modular domain structure for real-world features
- ✅ Robust validation (DTOs & Zod)
- ✅ Seed scripts for database population
- ✅ Example unit & E2E tests

**Use this as a starter template** for building production-ready backend services.

---

## ✨ **Project Goal**

This project serves as a **boilerplate** for teams or individuals who want to:
- Learn **NestJS** best practices
- Implement **auth flows** (JWT, Google OAuth)
- Use **role-based access control**
- Build well-structured modules (User, Property, etc.)
- Automate database seeding for dev/test environments

---

## ⚙️ **Features**

✅ **Authentication**
- Local strategy with username & password
- JWT Access & Refresh Tokens
- Google OAuth2 integration
- Custom Guards for auth & roles

✅ **Authorization**
- Role-based decorators & guards
- Public route decorators
- Flexible config files for JWT secrets

✅ **Entities & Modules**
- User management (CRUD)
- Property management (CRUD, DTOs, custom pipes)
- Property features & types

✅ **Database Seeding**
- Factory-based seeders for realistic data
- Easy local development setup

✅ **Validation**
- DTO classes with decorators
- Zod validation pipes for advanced use cases

✅ **Testing**
- Unit tests for services & guards
- E2E tests with Jest

---

## 🗂️ **Project Structure**



[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

