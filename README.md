# chrome-issue-1304217 EDIT 7/21/2022: Now an issue in Firefox. 
To test make sure to first install yarn if not already in you local dev enviroment. Yarn install will automatically download the required packages. Use  `yarn serve` to run the project locally. Once app started navigate to http://localhost:8080/dist/ for the index page. From there you will be able to see the issue in the Chrome/Edge DevTools Source Panel when you open the `webpack:// >> src >> home >> home.vue`.

Checkout source_panel image in project root. This shows what the source is currently. It should show the contents of Home.vue.

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
