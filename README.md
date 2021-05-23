# Udagram

Codebase of a full stack sample application to be hosted on AWS (S3, EB, RDS).

## Getting started

Provision the necessary AWS services needed for running the application:

1. Provision a publicly available AWS RDS database running Postgres.
2. Provision an AWS S3 bucket for hosting the uploaded files.
3. Export the ENV variables needed or use [dotenv](https://www.npmjs.com/package/dotenv).
4. `cd starter/udagram-api` and install the node_modules `npm install`.
5. After installation is done start the api in dev mode with `npm run dev`.
6. `cd starter/udagram-frontend` and intall the node_modules `npm install`.
7. sAfter installation is done start the api in dev mode with `npm run start`.

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Testing

This project contains two different test suites: unit tests and End-To-End tests(e2e). Follow these steps to run them: 

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)