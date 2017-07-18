# react-redux-apollo-authentication-example
An authentication flow example using GraphQL as a service provided by [Scaphold.io](http://scaphold.io)

## Includes
- React
- React Router
- Redux
- Apollo

## Setup the backend
- Create an account on [Scaphold.io](http://scaphold.io)
- Create your first App on the **Apps** menu.
- Then copy the endpoint from **My API** menu.

![Scaphold.io My API](https://s4.postimg.org/tfr6aehod/Screenshot_2017-07-18_09.51.08.png)

- Open the `config.json` file based on the root directory and change the `graphQLServiceUri` to your Scaphold app endpoint.

> You dont need to create any schema. Scaphold.io already provides a User schema designed for the needs of this project.

## Setup this project
```bash
yarn # or npm install
yarn start # or npm start
```

The project should be listening on [http://localhost:3000](http://localhost:3000)
