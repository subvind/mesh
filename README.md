mesh
========
ChatGPT: Mesh is a decentralized, federated app that is built using the NestJS framework and deployed on Heroku. The app uses a Hasura backend for data storage, and allows users to choose which node their information is stored on, or even run their own nodes. This enables decentralized data management, allowing users to own and control their own data, and easily access and manipulate it. They can also backup their data to other nodes for added security and reliability.

The app uses RxDB and CouchDB for data management, and utilizes Websocket Replication for efficient data synchronization between nodes. This enables node-to-node data transfer, allowing nodes to push and pull data between one another. A signaling server, coded in NestJS and running on railway.app, uses PusherJS to relay unique IDs between users. This enables them to make direct connections with one another using PeerJS, a library that allows for peer-to-peer communication within the app.

In conclusion, Mesh allows users to control their own nodes, and easily access, manipulate, and share their data with others. It also enables efficient data synchronization and communication between nodes and users, making it a flexible and powerful tool for a variety of use cases and applications.


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
