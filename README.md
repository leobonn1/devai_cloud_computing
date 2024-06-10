# devai-cloud-computing

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

## Dockerização
- Criação do Dockerfile
- docker build -t leobonn/devai-cloud-computing:v1 .
- docker run -it -p 8080:80 --rm --name devai-cloud-computing leobonn/devai-cloud-computing:v1
