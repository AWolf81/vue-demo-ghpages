# vue-demo-ghpages

Test project for deploying a Vue app with Vue-Router & history mode to github pages.

This Vue app is just the Vue-cli webpack template with one Vue route added to test deployment.

**Note**
Deployment is working if history mode is disabled. With history mode the routing is not working at gh pages.

Changed deployment to surge.sh because historyAPI is fully supported and deployment is easier.

> A Vue.js project

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

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
