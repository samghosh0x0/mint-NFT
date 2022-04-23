1. Use the .env file to update the your wallet public address and private key. 


If the .env file is not visible, enable view of hidden files.


2. Update the location of the asset-metadata in /scripts/mint-nft.js.


3. After you update the public keys, and private keys, asset-metadata location, you can mint new NFTs with the same contract by calling 

"node scripts/mint-nft.js" from the root of the folder. 

4. If you deploy a new contract, you have to update the contract address in /scripts/mint-nft.js.

5.This is created following this guide from Ethereum

https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/

Follow the steps to deploy smart contract and mint NFTs. 
