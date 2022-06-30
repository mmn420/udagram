# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Getting Started

1. Clone this repo locally into the location of your choice.
1. Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
1. Open a terminal and navigate to the root of the repo
1. follow the instructions in the installation step

The project can run but is missing some information to connect to the database and storage service. These will be setup during the course of the project

### Dependencies

```text
- Node v16 (LTS) or more recent.

- npm 5.5.1 (LTS) or more recent.

- AWS CLI v2, v1 can work but were not tested for this project

- AWS EB CLI

- AWS RDS database running Postgres.

- AWS S3 bucket for Frontend.

- AWS Elastic Beanstalk for Backend.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <database-1.c1kobdvxkexq.us-east-1.rds.amazonaws.com>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <http://mmn-udagram.s3-website-us-east-1.amazonaws.com>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd udagram/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd udagram/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## Deployment

- [http://mmn-udagram.s3-website-us-east-1.amazonaws.com](http://mmn-udagram.s3-website-us-east-1.amazonaws.com) - S3 Bucket - udagram-frontend

## Documents

### Click [here](https://github.com/mmn420/udagram/tree/main/Documentation) to open the Documents
