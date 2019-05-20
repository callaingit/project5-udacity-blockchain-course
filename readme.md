* Key items asked for
1) Your ERC-721 Token Name: Udacity Star Token
2) Your ERC-721 Token Symbol: UST
3) Version of the Truffle and OpenZeppelin used: truffle v5.0.18 and OpenZeppelin 2.1.2
4) StarNotary (token) contract address on Rinkeby: 0x9258B82FfdB5E64bafD22204b0C552d5c45BFD96
     See it here: https://rinkeby.etherscan.io/address/0x9258b82ffdb5e64bafd22204b0c552d5c45bfd96

* Other relevant information for this project
Account address I have used to deploy on Rinkeby : 0x17200924F93786c971d84e0Cd86d8e78cd479955
Migrations contract address on Rinkeby: 0x94dD0D30385338520E93244087461EB516e70550
Please note I have created Star9999 (id = 9999) using my contract on Rinkeby to test it out.
  If you create another star on Rinkeby with my contract, wait till the transaction is confirmed in metamask before querying for it
The provider for the network rinkeby in my truffle-confif.js assumes you have a file /tmp/.infura-secret with the infuraKey it in and a file /tmp/.mnemonic-secret with your HD Wallet seed (from metamask) in it

* Setup
I assume you have truffle installed (I had 5.0.18 installed globally)
Please run npm install openzeppelin-solidity@2.1.2 in the project directory in order to get its base contract for my token
Please run npm install truffle-hdwallet-provider@1.0.2 in the project directory in order to use rinkeby with truffle
Please run npm install in the app directory to get all the npm packages to run the web application
Run truffle develop in the project directory
  In truffle, run compile (just type compile) as the build directory is excluded in the .gitignore that we were provided with
  In truffle, run migrate --reset to deploy contracts locally
You will have to use truffle migrate --reset --network rinkeby to deploy contracts on rinkeby
You will have to run npm run dev from the app project folder to run the web server and go to http://localhost:8080 to use the DApp
