# Basic-Truffle-Dapp
Example Dapp with a very basic Contract demo. 

## Requeriments

Node + npm

Clone this repo:

`git clone https://github.com/armova/Basic-Truffle-Dapp.git`

&& run:

`npm install`

Install testrpc & truffle:

`npm install -g ethereumjs-testrpc`

[https://github.com/ethereumjs/testrpc](https://github.com/ethereumjs/testrpc)

`npm install -g truffle`

[https://github.com/ConsenSys/truffle](https://github.com/ConsenSys/truffle)

## Usage
Take a look at the project structure and make sure to review the package.json & webpack.config.json files.

You will be running testRPC as a local Ethereum network, using Truffle to compile and deploy the contract to testRPC, building the code with Webpack and finally running the Dapp in your browser and being able to make some basic modifications to the state of the contract. See the transactions being computed in the testRPC simulated Ethereum network.

#### Open a console and run:

`testrpc`

#### Open another console, go to your project directory, and run:

`truffle compile`

`truffle migrate`

`npm run build`

`truffle serve`

Open your app at:
[http://localhost:8080](http://localhost:8080)

## Continue learning from here:

#### Suggested reading
[Ethereum - Solidity, intro to smart contracts](https://solidity.readthedocs.io/en/develop/introduction-to-smart-contracts.html)

[Watch this video from min 39 to extend this contract behavior](https://youtu.be/8jI1TuEaTro?t=39m15s)

[Similar tutorial from Truffle with more complex Contracts](http://truffleframework.com/tutorials/building-testing-frontend-app-truffle-3)

[Web3 Javascript API Docs](https://github.com/ethereum/wiki/wiki/JavaScript-API)











