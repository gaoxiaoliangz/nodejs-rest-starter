# node-starter

A simple express-based node starter

## Features

- ejs
- express
- multer
- a simple mongodb wrapper

## How to run

```
yarn install
yarn watch
yarn dev
```

## deploy to zeit-now

### adding env vars

- <https://zeit.co/docs/v2/build-step/#adding-secrets>
- <https://zeit.co/blog/environment-variables-secrets>
- <https://zeit.co/docs/v2/advanced/configuration#env>

set secrets

```
now secret add mongodb-url <your-mongodb-url>
now secret add secret <your-secret-string>
```

these secrets are referenced in `now.json`
