# nodejs-security-2 [![Run CI](https://github.com/kkamara/nodejs-security-2/actions/workflows/node.js.yml/badge.svg)](https://github.com/kkamara/nodejs-security-2/actions/workflows/node.js.yml)

Hash, Encrypt and Decrypt with the NodeJS Crypto module.

## Installation

* [NodeJS](https://nodejs.org/en/)
* [Yarn](https://yarnpkg.com/)

```bash
  npm install --global yarn
  cp .env.example .env
  yarn install
```

## Usage

```bash
  yarn start # Runs Start-script `yarn node src/index.js`
```

```
MacBook-Air:nodejs-security-2 kel$ yarn start
yarn run v1.22.19
$ yarn node src/index.js
encrypted text 04f08299ad2c9d161426a84adffb324f:4cf2763f9c1bd14ec69390597a9c931d
decrypted text Hello World
✨  Done in 0.47s.
MacBook-Air:nodejs-security-2 kel$ vim src/encryption.js
```

## To run api tests

```bash
  yarn test
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD](https://opensource.org/licenses/BSD-3-Clause)
