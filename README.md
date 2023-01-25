# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It came with a default contract, that i replaced with "SimpleStorage" contract, which stores a number on the block chain, and retrieves that number. In my project folder, I have four main folders used for testing, creating scripts, and creating new hardhat tasks. 

# .env file

my .env file contains user sensitive data, such as a test-net wallets private key, a rpc_url to connect hardhat to the needed test-net, as well as api keys from etherscan. 

In my previous projects, I did not use hardhat, and had to use my own EVM in ganache and get my own rpc_url and private keys from there. In that project, i encryped my private key and private key password and stored the encrypted values in a separate json file. As for my process of encrypting my key and password i used a built in method in the ethers.js package called "encrypt". encrypt in a method that uses a previously declared wallet variable ( const wallet = new ethers.Wallet(private_key)) and takes two parameters. The wallets private key password, and the wallets private key, 

-- WIP

# hardhat.config.js

# sol contract
