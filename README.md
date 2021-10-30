# hardhat-react

### How to integrate Smart Contracts with ReactJs

* Clone repo

`npm install`

* Compile
`npx hardhat compile`

* Test your contract
`npx hardhat test`

### Integrating with Front-End

* Go to Frontend directory
`cd frontend`

* Start hardhat node
`npx hardhat node`

* LocalHost
`npx hardhat run script/deploy.js --network localhost`

### Deploy
* Standard Deploy
`npx hardhat run scripts/deploy.js`

* Rinkeby network - Ethereum test network (Using infura)
`npx hardhat run script/deploy.js --network rinkeby`

* LocalHost
`npx hardhat run script/deploy.js --network localhost`