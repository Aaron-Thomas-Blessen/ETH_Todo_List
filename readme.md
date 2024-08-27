# ETH To-Do List

## Description
This is an Ethereum-based To-Do List application that leverages smart contracts to store tasks on the blockchain. The project is built using **Truffle**, **Ganache**, and **Node.js**, and is integrated with **MetaMask** for interacting with the Ethereum network.

## Features
- **Smart Contract for Task Management**: Tasks are created, stored, and managed on the Ethereum blockchain.
- **Blockchain Interaction**: Interact with the smart contract using Truffle and MetaMask.
- **Persistent Storage**: Tasks are securely stored on the blockchain, ensuring data integrity.

## Technologies Used
- **Ethereum**: Blockchain platform for the smart contract.
- **Solidity**: Programming language for writing the smart contract.
- **Truffle**: Development framework for Ethereum.
- **Ganache**: Personal Ethereum blockchain for local development.
- **Node.js**: JavaScript runtime for running the application.
- **MetaMask**: Browser extension for interacting with the Ethereum blockchain.

## Prerequisites
- **Node.js** installed on your machine.
- **Ganache** installed for running a local Ethereum blockchain.
- **Truffle Framework** installed globally: 
  ```bash
  npm install -g truffle@5.0.2
  ```
- **MetaMask** wallet added as a browser extension.

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Aaron-Thomas-Blessen/ETH_Todo_List.git
cd eth-todo-list
```

### 2. Initialize the Truffle Project
```bash
truffle init
```

### 3. Create `package.json`
```bash
touch package.json
```

### 4. Install Dependencies
```bash
npm install
```

### 5. Compile the Smart Contract
```bash
truffle compile
```

### 6. Migrate the Smart Contract to the Blockchain
```bash
truffle migrate
```

### 7. Interact with the Smart Contract
```bash
truffle console
```

### 8. Deploy and Test
```bash
todoList = await TodoList.deployed()
todoList
todoList.address
taskCount = await todoList.taskCount()
taskCount.toNumber()
task = await todoList.tasks(1)
truffle(development)> task
```

## Usage
1. **Run Ganache**: Start your local Ethereum blockchain.
2. **Compile the Contract**: Use `truffle compile` to compile the smart contract.
3. **Deploy to Blockchain**: Use `truffle migrate --reset` to deploy the contract to the blockchain.
4. **Interact with Contract**: Use the Truffle console to interact with the deployed contract.

## Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.



install Ganache

install Node.js

install Truffle framework
$ npm install -g truffle@5.0.2

add it to environment if needed

add metamask wallet as extension

$ mkdir eth-todo-list
$ cd eth-todo-list

truffle init

touch package.json

npm install

truffle compile

truffle migrate

truffle console

todoList = await TodoList.deployed()

todoList

todoList.address

todoList.taskCount()

taskCount = await todoList.taskCount()     

taskCount.toNumber()

created a smart contract
create a truffle project
connected to blockchain
put smart contract to blockchain and talk to it

truffle compile

truffle migrate --reset

task = await todoList.tasks(1)

truffle(development)> task
