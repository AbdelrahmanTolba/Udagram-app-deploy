# Udagram Api App

> This project is part of the Udacity FullStack JavaScript nanodegree. The code was given as a starter project and the task was to employ and adapt the code to get it working and hosted on AWS

### Build with

- [Angular](https://angular.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [NodeJS](https://nodejs.org/en/)
- [Expressjs](https://expressjs.com/)
- [postgresql](https://www.postgresql.org/)
- [AWS CLI](https://aws.amazon.com/)
- [RDS](https://us-east-1.console.aws.amazon.com/rds/home?region=us-east-1#)
- [S3](https://s3.console.aws.amazon.com/s3/get-started?region=us-east-1)
- [Elastic Beanstalk](https://us-east-1.console.aws.amazon.com/elasticbeanstalk/home?region=us-east-1#/welcome)

# Getting Started

1. **_Clone the repository_**

```sh
$ git clone [https://github.com/AbdelrahmanTolba/deploy-udagram]
```

2. **_Navigate to repository directory_**

```sh
$ cd deploy-udagram
```

3. **_Install dependencies_**

```sh
$ npm install
```

# Deploy on local

## Server side

1. **_Navigate to udagram-api folder_**

```sh
$ cd udagram/udagram-api
```

2. **_Create `.env` file_**

```sh
    PORT=8080

    POSTGRES_HOST="127.0.0.1"
    POSTGRES_USERNAME = "abdelrahmantolba"
    POSTGRES_PASSWORD= "password123"
    POSTGRES_DB= "udagram"

    URL= "http://localhost:8080"
    JWT_SECRET="mysecretstring"
```

3. **_Create user and database has same name from env file_**

4. **_build project_**

```sh
$ npm run build
```

5.  **_run server project_**

```sh
$ npm run dev
```

## Client side

1. **_Install dependencies_**

```sh
$ npm install
```

2.  **_build project_**

```sh
$ npm run build
```

3.  **_run server project_**

```sh
$ npm run start
```

# Deploy on AWS

AWS services needed for running the application:

- RDS - In AWS, provision a publicly available RDS database running Postgres
- S3 - In AWS, provision a s3 bucket for hosting the uploaded files.
- EB - Container for services

# Running App

![running application](https://user-images.githubusercontent.com/90225424/193299843-000a35cf-4974-488f-8d21-20235f902d6f.png)
