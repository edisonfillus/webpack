# webpack

### Client
```console
user@host:~/webpack/client$ npm install
user@host:~/webpack/client$ npm run watch
```

### Server
```console
user@host:~/webpack/client$ npm run
```


### Include webpack and babel in new project
```console
user@host:~/webpack/client$ npm install webpack webpack-cli babel-core@6 babel-loader@7 babel-preset-env --save-dev
```

### Build
```console
user@host:~/webpack/client$ npm run build-dev
```

### Webpack Dev Server
```console
user@host:~/webpack/client$ npm install webpack-dev-server --save-dev
```

### CSS / Image / Fonts Loaders
```console
user@host:~/webpack/client$ npm install css-loader url-loader file-loader mini-css-extract-plugin --save-dev
```

### Minify and Optimize CSS
```console
user@host:~/webpack/client$ npm install optimize-css-assets-webpack-plugin --save-dev
```

### Bootstrap / JQuery
```console
user@host:~/webpack/client$ npm install jquery popper bootstrap --save
```
```js
import 'bootstrap/dist/css/bootstrap.css';
```