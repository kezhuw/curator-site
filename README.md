# Apache Curator Official Website

This project keeps all sources used for building the Apache Curator official website, which is served at https://curator.apache.org/.

## Prerequisite

The Apache Curator website is powered by [Docusaurus 2](https://docusaurus.io/) and is built with Node 19 and Yarn 3. Check the [deployment workflow](.github/workflows/deploy.yml) for concrete requirements and instructions.

## Installation

```shell
yarn
```

## Local Development

```shell
yarn start
```

This command starts a local development server and opens a browser window. Most changes are reflected live without having to restart the server.

## Build

```shell
yarn build
```

This command generates static content into the `build` directory and can be served using any static content hosting service.
