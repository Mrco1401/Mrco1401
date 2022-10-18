# Bevvies - Auto Mint Bot

### Dev

```shell
yarn install
yarn start-local-network # Starts Hardhat Network on localhost
yarn deploy-local-contract # Deploy a sample smart contract to localhost
yarn dev # Starts the bot service and connects to Hardhat Network on localhost
```

### Testing

```
yarn start-local-network # Starts Hardhat Network on localhost
yarn test:integration # Run integration tests
```

### Build / Deploy

```shell
yarn build # Compile ts files to js in dist folder
yarn start # Starts the bot service and connects to Ethereum Mainnet
```

### Other commands

```shell
npx eslint '**/*.{js,ts}'
npx eslint '**/*.{js,ts}' --fix
npx prettier '**/*.{json,sol,md}' --check
npx prettier '**/*.{json,sol,md}' --write
npx solhint 'contracts/**/*.sol'
npx solhint 'contracts/**/*.sol' --fix
```
