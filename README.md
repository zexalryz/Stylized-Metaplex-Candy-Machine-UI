# Stylized Metaplex Candy-Machine-UI

This is a edited version of METAPLEX Candy-Machine-UI who look plain connect.
i just add some styling, you can edit the theme, or background color at css gradient tool.


## Getting started
Required :
```
    node 16.13.0
    npm
    yarn 1.22 (npm install yarn)
    npm install -g typescript
    npm install -g ts-node

```

then enter the clone repo folder

and type :
```
npm install
or
yarn install
```



### Rename the .env.example file to .env and populate the following environment variables:

Required:

```
- REACT_APP_CANDY_MACHINE_ID
- REACT_APP_SOLANA_NETWORK=
- REACT_APP_SOLANA_RPC_HOST=
```


### Example configuration
Devnet:
```
- REACT_APP_SOLANA_NETWORK=devnet
- REACT_APP_SOLANA_RPC_HOST=https://explorer-api.devnet.solana.com
```

Mainnet-beta:
```
- REACT_APP_SOLANA_NETWORK=mainnet-beta
- REACT_APP_SOLANA_RPC_HOST=https://api.mainnet-beta.solana.com
```

### Edit the following variables in '../src/Home.tsx' to match your project:


### Then run:

```
- yarn install
- yarn dev
```
