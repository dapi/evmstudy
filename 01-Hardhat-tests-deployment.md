# 01 -- Hardhat, tests, deployment

https://code.visualstudio.com/
https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity

## Hardhat

https://nodejs.org/en/
https://hardhat.org/

```
npm install --save-dev hardhat
```

https://docs.ethers.io/v5/
https://www.npmjs.com/package/ethereum-waffle
https://getwaffle.io/


## Разные сети и Hardhat local node

https://metamask.io/

Фикс конфига hardhat для Метамаска

```
module.exports = {
  solidity: "0.8.4",
  networks: {
    hardhat: {
      chainId: 1337,
    },
  },
};
```


## Настройка hardhat

https://hardhat.org/config/
https://hardhat.org/plugins/


## Deployment

https://ethereum.org/en/developers/docs/networks/
https://docs.fantom.foundation/tutorials/set-up-metamask-testnet

