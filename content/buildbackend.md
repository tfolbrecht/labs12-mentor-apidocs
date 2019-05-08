---
weight: 5
title: Building the Project Backend
---

# Building the Node backend

### Clone the repo

`git clone git@github.com:labs12-mentor/labs12-mentor-BE.git`

```shell
# clone the repo to your local machine
git clone git@github.com:labs12-mentor/labs12-mentor-BE.git`
```


### Install the dependencies

```shell
# Install the dependencies
npm install
```

### Configure the Database with Knex

We use PostgreSQL for our development environment

#### Create the Tables with the command

`npx knex --env development migrate:latest`

```shell
# create the Tables with the command
npx knex --env development migrate:latest
```

#### Seed the DB

`npx knex --env development seed:run`

```shell
# seed the DB
npx knex --env development seed:run
```

### Start the Server

`npm run start`

```shell
# start the Server
npm run start
```

Runs the app in the development mode.

`npm run server`

```shell
# start the server with watch (nodemon)
npm run server
```

Launches the test runner in the interactive watch mode.

`npm run test`

```shell
# runs jest tests
npm run test
```

Builds the jests tests in `--watch --verbose` mode according to the package.json config