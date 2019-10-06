## DEV Environment
1. Node.js v8+ LTS and npm (comes with Node)
2. Git
3. Metamask 
4. Truffle
5. Ganache


## Steps to run this
> Clone the repo
> Install truffle
	npm install -g truffle
> Install Ganache	
> Make sure you are in the root of your project directory
  	truffle compile
> Before migrating the contract to the blockchain we need to have a blockchain running. 
	Open Ganache - Will generate a local blockchain
> Migration
	truffle migrate
>Run test
	truffle test

## Using the dapp
> In the root of your project directory 
	npm run dev

> The dev server will launch automatically in a new tab in the browser opening your dapp.

> A MetaMask pop-up should appear requesting your approval to allow Petto to connect to your MetaMask wallet. Without explicit approval, you will be unable to interact with the dapp.

> In metamask, top left corner, Connect to your local blockchain server - http://127.0.0.1:9545/

> Login to the dapp using "Torus login" icon (bottom left)

> Click the Adopt button on the pet of your choice.

> You'll be automatically prompted to approve the transaction by MetaMask. Click Submit to approve the transaction.

> You'll see the button next to the adopted pet change to say "Success" and become disabled, because the pet has been adopted.

> In Metamask you will see the transaction listed.

## More
This is a fully functional dapp which can be modified further to storing "Collectables"
