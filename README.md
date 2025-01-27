# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

To access the website `http://udagram-bucket976183147044.s3-website-us-east-1.amazonaws.com/`

![image](./screenshots/frontend.png)

### Dependencies

```
- Node v14.15.5 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

1. clone this repo
2. setup .env file

```
POSTGRES_USERNAME=db_username
POSTGRES_PASSWORD=db_password
POSTGRES_DB=udagram
POSTGRES_HOST=host_url
URL=s3_url
JWT_SECRET=secret
PORT=8080
RDS_DIALACT=postgres
AWS_BUCKET=bucket_name
AWS_ACCESS_KEY_ID=aws_user_key
AWS_SECRET_ACCESS_KEY=aws_user_password
AWS_DEFAULT_REGION=region
```

3. install api dependencies `npm run frontend:install` then run api `npm run api:start`
4. install frontend dependencies `npm run frontend:install` then run frontend `npm run frontend:start`

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

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
