# vue-rest-node


Create developer account at Okta:
https://developer.okta.com/signup/

Select Application tab and create new application and after creation, note down the clientid. Need to use clientid in server.js router/index.js.
https://dev-322001.oktapreview.com/oauth2/default : issuer

Start node server with : node ./src/server 
> A Vue.js project


Start frontend with
npm install (make sure you installed all packages as mentioned in package.json, with npm install command)
npm start

Navigate to http://localhost:8080 and create and delete posts.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
