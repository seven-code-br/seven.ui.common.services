# S7 - UI: Common Services

This is the repository of the seven.ui.common.services library.
This project was generated with [Angular CLI](https://github.com/angular/angular-cli).

## Setup / Installation

> Warning: This application requires [Node.js](https://nodejs.org/) to run.

Install the frameworks dependencies:

```sh
  // Angular CLI
  npm install -g @angular/cli@11.2.4
```

Install the npm packages dependencies:

```sh
  npm install
```

## Commands for Test and Build Application

Commands list

```sh
  // Tests
  $ npm run test // With Watch
  $ npm run test:prod  // With Reports

  // Documentation
  $ npm run docs

  // Code Quality
  $ npm run sonar // Sonar must be started

  // Versioning
  // Patch: v0.1.8
  $ npm run release:patch
  // Minor: v0.2.0
  $ npm run release:minor
  // Major: v1.0.0
  $ npm run release:major

  // Build
  $ ng build
  $ npm run build:prod // Release pack
```

## Dependencies

Common Services uses the following frameworks.

> Waring: Be cautious when upgrading any frameworks.
> Info: Instructions on how to use the frameworks are available in the documentation.

| Package          | Version | Documentation                                                                                                                  |
| ---------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Compodoc         |  1.1.11 | [https://compodoc.app/guides/getting-started.html](https://compodoc.app/guides/getting-started.html)                           |
| commitlint       | 12.0.1  | [https://commitlint.js.org/](https://commitlint.js.org/)                                                                       |
| gulp             |  4.0.2  | [https://gulpjs.com/docs/en/getting-started/quick-start](https://gulpjs.com/docs/en/getting-started/quick-start)               |
| husky            |  6.0.0  | [https://typicode.github.io/husky/](https://typicode.github.io/husky/)                                                         |
| sonnar-scanner   |  3.1.0  | [https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/) |
| standard-version |  9.1.1  | [https://github.com/conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version)       |
