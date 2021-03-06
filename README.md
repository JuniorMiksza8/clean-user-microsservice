[![Build and test Node application](https://github.com/JuniorMiksza8/clean-user-microsservice/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/JuniorMiksza8/clean-user-microsservice/actions/workflows/test.yml)

# Description

    Clean Typescript API made with NodeJS,Express and Prisma

# Features

    - Tested with JEST
    - Error reports with Sentry.IO
    - Dockerized
    - padronized HTTP error handling

# Setup

#### Development

      Requirements
        - Docker ( for the database ) or Postgres installed
        - NodeJS

        run npm install or yarn on the root folder to install the required packages.
        run cp .env.example .env and fill in required environment variables
        run npx prisma migrate deploy to sync database
        run npm run dev to serve the server on the choosen env { SERVER_PORT }


#### Production

        Requirements
          - Docker

          Inject environment variables
          run docker-compose up




### Workspace import data available on the Postman folder in the repository
