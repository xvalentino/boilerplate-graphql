# Handshake Code Challenge Graphql Boilerplate

## API

This repo uses a Prisma backed API.
[prisma](https://www.prisma.io/docs/understand-prisma/)
[writing migrations in prisma](https://www.prisma.io/docs/get-started/02-change-data-model-JAVASCRIPT-c001/)
depends on docker + node

Setup locally with `docker-compose up -d`
To deploy your Prisma API locally after making changes to the schema, run `yarn deploy`

Once the server is running, you can interact with the Graphql API at http://localhost:4466/

## Front end

### Parcel

The front end is hosted by [parcel](https://parceljs.org)

Serve front end assets with `yarn start` on localhost:1234

### React

The front end is setup with React + Apollo to see data. See client/index.js
