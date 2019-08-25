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

### CSS Loaders
```console
user@host:~/webpack/client$ npm install css-loader style-loader url-loader --save-dev
```

### Bootstrap / JQuery
```console
user@host:~/webpack/client$ npm install jquery popper bootstrap --save
```
```js
import 'bootstrap/dist/css/bootstrap.css';
```