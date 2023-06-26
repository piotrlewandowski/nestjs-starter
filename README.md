# NestJS Starter

This is a NestJS Starter based on [Nest](https://github.com/nestjs/nest).

## Prerequisites

- [Node](https://nodejs.org/) (Make sure you have the node 14+ installed)

## Getting Started

1. Clone the repository `gh repo clone piotrlewandowski/nestjs-starter` (or if you're not using GitHub CLI: `git clone git@github.com:piotrlewandowski/nestjs-starter.git`)
2. If you're using NVM run `nvm use` inside project directory to use node version set in `.nvmrc` file
3. Run `yarn install` to install all the dependencies
4. To begin development task, run `yarn start:dev`
5. Open [http://localhost:3000/api](http://localhost:3000/api)

## Available commands

### Running the app

```bash
# delete the `dist` folder
$ yarn clean:dist

# start the app in the development mode
$ yarn start

# start the app in the development mode and watch for changes
# the app will reload if you make edits.
$ yarn start:dev

# start the app in the debug mode and watch for changes
$ yarn start:debug

# start the app in the production mode
$ yarn start:prod
```

### Testing

```bash
# unit tests
$ yarn test

# unit tests and watch for changes
$ yarn test:watch

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:coverage

# test debug mode
$ yarn test:debug
```

### Building

```bash
# build the app
$ yarn build
```

### Linting

```bash
# execute eslint check
$ yarn eslint:check

# execute eslint check and automatically fix issues
$ yarn eslint:fix

# format the code
$ yarn format
```

## Contacts

- Author - [Piotr Lewandowski](https://piotrlewandowski.info)

