# frontend-trial-workday

## Project setup
```
npm install
```

### Use JSON server as mock api
```
npm run server
```

Per default the JSON server is using `http://localhost:3000`. You will have the following endpoints available:

- `GET /tools` to get a list of all available tools
- `GET /tools?_expand=team` to get a list of all available tools with the expanded team (recommended)
- `POST /tools` to create a new tool
- `GET /teams` to get a list of all available teams

Checkout `db.json` to see the basic structure. Since this package is completely relying on [json-server](https://github.com/typicode/json-server) you can find more detailed information there if needed.

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

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
