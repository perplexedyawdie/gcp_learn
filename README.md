<h1 align="center">Welcome to Express App Demo 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/Express App Demo" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/Express App Demo.svg">
  </a>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> Dockerized Express App

## Install

```sh
npm install
```

## Usage

### Local
```sh
npm run start
```

### Docker
```sh
docker build -t express-app .

docker run -dp 3000:3000 express-app
```

### Cloudbuild
1. Create a service account that has permissions on Cloud Build, Compute & Artifact Registry.
2. Push the code to a GCP Code Source repo.
3. In Artifact Registry, create a Docker repo.
4. Copy the image tag & push location in the cloudbuild file.
5. Create a private pool in Cloud build.
6. Create a trigger in Cloud build. 

## Author

👤 **Javel Rowe**

* Website: https://dev.to/perplexedyawdie
* Github: [@perplexedyawdie](https://github.com/perplexedyawdie)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_