This repository demonstrates my Solidity skills with a simple Ethereum-based smart contract. The contract allows users to deposit and withdraw Ether securely, while logging all transactions for transparency.

About the Project

MyContract is designed to provide:
	•	A way for users to deposit and withdraw Ether.
	•	Balance tracking for individual users.
	•	Transaction logging via events for better visibility.

This project is part of my submission for the Boba Code Badge and highlights my ability to write, test, and deploy Solidity-based smart contracts.

Features

	1.	Owner Assignment: The contract automatically assigns the deployer as the owner.
	2.	Ether Deposits: Users can deposit Ether, and their balances are updated.
	3.	Safe Withdrawals: Withdrawals are only allowed if the user has sufficient funds.
	4.	Event Logging: Logs deposits and withdrawals to ensure transparency.

Files Included

	1.	MyContract.sol: The main contract implementing deposit and withdrawal functionality.
	2.	MyContract.test.js: Unit tests verifying the contract’s features and behavior.
	3.	deploy.js: A script for deploying the contract to an Ethereum network.

How to Use

To try out the project, follow these steps:
	1.	Clone the repository:

git clone 
 


	2.	Install dependencies:

npm install  


	3.	Run tests to verify functionality:

npx hardhat test  


	4.	Deploy the contract:

npx hardhat run scripts/deploy.js --network localhost  

Purpose

This project is designed to demonstrate:
	•	Safe handling of Ether transactions in Solidity.
	•	Event-driven programming for better transparency.
	•	My ability to write clean and well-documented smart contract code.
