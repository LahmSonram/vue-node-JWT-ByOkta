# vue-node-start

``` bash
# A Vue.js And Node.js project
# Okta jwt verifier 
# Finale-rest // Create the dynamic REST resource
# Sequelize // promise-based ORM for Node.js
```

## Okta
you will need to create an OIDC application in Okta. Sign up for a forever-free developer account
``` bash
> https://developer.okta.com/signup/
>> create a new application by clicking “Add Application”.
>> Select the “Single-Page App” platform option.

> You’ll need to replace {yourOktaDomain} and {clientId} which can be found on your application overview page in the Okta Developer Console.
  src/router/index.js and src/server.js
  
  issuer: 'https://{yourOktaDomain}/oauth2/default',
  client_id: '{clientId}',
```
### Build Setup

``` bash
# install dependencies
npm install

# run server node js at localhost:8081
node ./src/server

# serve with hot reload at localhost:8080
npm run dev

```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

https://developer.okta.com/blog/2018/02/15/build-crud-app-vuejs-node
