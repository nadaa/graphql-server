# graphql-server


### Data

#### Static data
imported from `@groceristar/groceristar-fetch` plugin
More about this plugin [here](https://medium.com/groceristar/groceristar-fetch-small-module-that-weve-created-8b4a62bd5d7b): 

#### Database schema
![schema](https://raw.githubusercontent.com/ChickenKyiv/database-visuals/master/Groceristar%20%20%20SqlDBM.png)
Details about current DB scheme: https://medium.com/groceristar/database-schema-of-groceristar-current-release-20dc1b4be7b9

This is a strucuture that we have in our models:
https://github.com/ChickenKyiv/database-visuals/tree/master/groceristar/models
same structure we use at groceristar-fetch, so we can easy grab data, that we need.
database(we'll use it later):
```
"url": "mongodb://heroku_p3w65n77:h3ab8q3uaqdk7tjrauhbl7dd6r@ds235065.mlab.com:35065/heroku_p3w65n77",
"name": "groceryDS",

```

### Rest API methods
This is a list of methods, that we have in our Frontend Version.
I can be like a checklist for us. In order to fully migrate from REST API server to graphQL we'll need to cover all of this cases: https://medium.com/groceristar/groceristar-website-methods-list-75b57e1414ae


 ### GroceryStar Documentation
 This is our main documentation space, related to Groceristar project: https://groceristar.github.io/documentation/


### Running the development server

```
npm install
```
Graphql server will be running in http://localhost:3000/

You can explore all schema types

![](https://i.imgur.com/YIGJRJH.png)


### GraphQL Resources
I have some collection of tutorials, websites, related to GraphQL topic, storing it here: https://github.com/ChickenKyiv/awesome-graphql-beginner-links
