
## Requirements

* Python 3.10+
* Poetry
* Node.js 14+
* Yarn
* Docker
* Docker-compose

## Build & run

#### Indexer

```
docker-compose up -d --build
```

#### SDK

```
yarn
yarn build
yarn link
```

#### UI

```
yarn
yarn link demo-sdk
yarn serve
```
