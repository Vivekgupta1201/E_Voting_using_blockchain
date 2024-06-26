# E_Voting_using_blockchain
## snapshorts
![Screenshot (221)](https://github.com/Vivekgupta1201/E_Voting_using_blockchain/assets/122138413/a7569623-c2ed-4d7a-8ffa-00cab10da51f)
![Screenshot (220)](https://github.com/Vivekgupta1201/E_Voting_using_blockchain/assets/122138413/8a51de64-e0f5-43a8-a44e-365d5b15c863)
![Screenshot (218)](https://github.com/Vivekgupta1201/E_Voting_using_blockchain/assets/122138413/8acb861c-4175-4514-b707-e2a817b0a221)
![Screenshot (217)](https://github.com/Vivekgupta1201/E_Voting_using_blockchain/assets/122138413/7104b8a7-2dc4-4fd7-b6ae-ce33f75e0bfd)
![Screenshot (223)](https://github.com/Vivekgupta1201/E_Voting_using_blockchain/assets/122138413/7c27e4c0-7630-4471-b998-ffaa2dc30c82)


To run the code, you need to run the following commands. 

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.


```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. 
You can also use another blockchain by writing the blockchain's endpoint in hardhat-config. 

Once you have pasted your private key and contract address in the .env file, simply run command 

```shell
node index.js
```

and go to http://localhost:3000 to interact with the decentralized voting application.

