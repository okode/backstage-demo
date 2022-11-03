# [Backstage](https://backstage.io)

## Requirements

* Node 16
* Yarn
* Docker / Docker Compose

## Build and running

```sh
yarn install --frozen-lockfile
yarn tsc
yarn build
docker-compose build
docker-compose up
```

Open Chrome on http://localhost:7007

## Develop

```sh
yarn install
yarn dev
```
