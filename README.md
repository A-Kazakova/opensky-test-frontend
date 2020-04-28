## opensky-test-frontend

Frontend for the [OpenSky](https://opensky-network.org/apidoc/rest.html) test project.

DEV: http://localhost:3000

STAGE: https://opensky-test-react.herokuapp.com

### Deploy

```shell script
git clone https://github.com/A-Kazakova/opensky-test-frontend
cd ./opensky-test-frontend
nvm use 12.16.2
npm i -g yarn
yarn install
```

### Environemnt

You can provide the `.env` file for the environment variables.

See the [`.env.example`](.env.example) for details.

### Launch

```shell script
yarn dev
```

### Build

```shell script
yarn build
```

### Heroku

The `stage` branch is automatically deployed to Heroku.
