# vue-github-actions

Simple workflow to deploy /dist on GitHub Pages.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Host on GitHub Pages
```
gh-pages -d dist
```

### Add this to vue.config.js

```
module.exports = {
    publicPath: '/vue-github-actions/'
}
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
