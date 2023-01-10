# SSV Scanner

![GitHub](https://img.shields.io/github/license/bloxapp/ssv-keys)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/bloxapp/ssv-keys/Lint%20and%20test)
![GitHub package.json version](https://img.shields.io/github/package-json/v/bloxapp/ssv-keys)

![GitHub commit activity](https://img.shields.io/github/commit-activity/y/bloxapp/ssv-keys)
![GitHub contributors](https://img.shields.io/github/contributors/bloxapp/ssv-keys)
![GitHub last commit](https://img.shields.io/github/last-commit/bloxapp/ssv-keys)

![GitHub package.json dynamic](https://img.shields.io/github/package-json/keywords/bloxapp/ssv-keys)
![GitHub package.json dynamic](https://img.shields.io/github/package-json/author/bloxapp/ssv-keys)

![Discord](https://img.shields.io/discord/723834989506068561?style=for-the-badge&label=Ask%20for%20support&logo=discord&logoColor=white)

Important dependencies:

* ![GitHub package.json dependency version (prod)](https://img.shields.io/github/package-json/dependency-version/bloxapp/ssv-keys/web3?style=social)

---

Library and CLI to work with the SSV scanner:
1. Retrieve the latest cluster data snapshot from the blockchain

## Running from the CLI

### Installation

This installation requires NodeJS on your machine.
You can download it [here](https://nodejs.org/en/download/).

Once you have installed NodeJS, follow instructions:

```bash
git clone https://github.com/bloxapp/ssv-scanner.git
cd ssv-scanner
npm run cli --help
```

### Running from repository

- For regular CLI usage you will be running the command as: `npm run cli ...`
- Follow [installation](#Installation) instructions.


### Help

Help on available actions:

```bash
npm run cli --help
```

Help on a specific action:

```bash
npm run cli <action> --help
```


### Example

**Input parameters:**

- node-url (n) = The ETH1 node url
- ssv-contract-address (ca) = Keystore password
- owner-address (op) = Cluster owner address
- operator-ids (oids) = Comma separated operator ids list

```bash
npm run cli -n .... -ca .... -oa ..... -oids=1,2,3,4
```

**Output:**  serialised cluster data

## Integration in your projects

### Node Project

To run an example of a NodeJS project containing all the code snippets to build the share and transaction payload, simply follow these instructions!

```bash
cd examples/node
npm install
```

To run a JavaScript example:

```bash
npm run start
```

## Development

### Run the CLI as a TypeScript executable:

```bash
yarn dev:cli ...
```

### Run the CLI as a JavaScript compiled executable:

```bash
yarn cli ...
```

### Lint

```bash
yarn lint
```

### Building

Build TypeScript into JavaScript

```bash
yarn build
```

Build for NodeJs using `esbuild`

```bash
yarn esbuild
```

Build everything

```bash
yarn build-all
```

## TODO


## Authors

* [Wadym](https://github.com/vadiminc)

## License

MIT License
