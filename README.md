# **UCB FinTech Bootcamp Module 20 Challenge**
# *Crypto Savings : Smart Contract in the Ether Blockchain*
## **Introduction**
### The Bootcamp Module 19 Challenge - Crypto Savings : Smart Contracts in the ETH Blockchain requires the creation of a Smart Contract to conduct crypto transactions as needed (e.g. deposits and withrdrawals from a crypto joint savings account). Using the Remix IDE for Ether, the contract should automatically keep track of the current contract balance to ensure accurate withdrawals and avoid overdrafts. In addition, the contract is to use require statements to provide security checks and prevent unauthorized withdrawals and ensure sufficient funds for withdrawals.
---
## **Technologies and Tools**
### The following list includes the main technologies and tools using during the preparation and deployment of the solution:
### 1. *GitHub* - Repository for code deployment, version management and documentation of the presented solution
### 2. *Visual Studio Code* - IDE tool for coding, code testing/debugging and text editing for the present README file
### 3. *Git Bash console* - Local console used to deploy the solution to GitHub. Version 2.40.0.windows.1 was utilized
### 4. *Slack* - Collaboration tool to communicate and brainstorm with other FinTech Bootcamp participants
### 5. *Operative System* - This solution was prepared in a PC running Windows 11 v H22
### 6. *[Solidity](https://solidity.readthedocs.io/)* - Solidity is the programming language used to write smart contracts on the Ethereum platform. It is a statically-typed, contract-oriented language designed for creating decentralized applications (dApps) on the Ethereum blockchain.
### 7. *[Remix IDE](https://remix.ethereum.org/)* - Remix is an online Integrated Development Environment (IDE) for writing, testing, and deploying smart contracts on the Ethereum blockchain. It provides a user-friendly interface and tools for developers to interact with their contracts on the JavaScript Virtual Machine (JavaScript VM) for testing and on real Ethereum networks for deployment. The program interacts with the Ethereum blockchain using the Remix IDE's JavaScript VM, which provides a simulated blockchain environment for testing purposes. It allows developers to deploy and test smart contracts without incurring real transaction costs on the live Ethereum network
---
## **Installation Guide**
### Since the contract does not use any external packages or libraries, all the functionality is native to Solidity and the Remix IDE environment.
---
## **Solution Structure**
### The **[20.CryptoSavings](https://github.com/LUTOV001/20.CryptoSavings)** repository in GitHub contains the solution components. The repository consists of the following folders and contents as described below:
 ###   *1. Execution Results :* Contains the screenshot files showing the results of interacting with the contract in the Remix environment.
###   *2. gitignore :* Instructions for which files/file types to exclude from the sync process between GitHub and the local environment.
###   *3. README.md :* The present file containing this outline of the challenge and its components and results.
###   *4. joint_savings.sol* This is the Solidity program with the code for the challenge solution.
---
## **User Instructions**

### To interact with the `JointSavings` smart contract, you can use the Remix IDE, which provides a simple way to interact with smart contracts deployed on the JavaScript VM as follows:

### 1. **Open Remix IDE**: Go to the Remix IDE website (https://remix.ethereum.org/) and start a new project by clicking on the "+" button in the top left corner. Save the project with an appropriate name.

### 2. **Copy the Contract Code**: Copy the `JointSavings` smart contract code and paste it into the Remix IDE editor.

### 3. **Compile the Contract**: In the Remix IDE, go to the "Solidity Compiler" tab on the left sidebar. Click on the "Compile JointSavings.sol" button to compile the contract. Make sure there are no compilation errors.

### 4. **Deploy the Contract**: After the contract is successfully compiled, switch to the "Deploy & Run Transactions" tab on the left sidebar. In the "Deploy" section, select the contract named "JointSavings" from the dropdown menu. Click on the "Deploy" button to deploy the contract to the JavaScript VM.

### 5. **Set Joint Account Owners**: In the "Deployed Contracts" section, you will see the deployed `JointSavings` contract. To set the joint account owners, enter the addresses of the two owners (e.g., `0x123...` and `0x456...`) in the "setAccounts" section. Click on the "transact" button to execute the transaction. This will set the joint account owners.

### 6. **Deposit Ether**: To deposit ether into the joint savings account, enter an amount in the "deposit" section and click on the "transact" button. This will send the specified amount of ether to the joint savings account.

### 7. **Check Contract Balance**: In the "deployed Contracts" section, you will see the contract details. The "contractBalance" variable shows the current balance of the joint savings account.

### 8. **Withdraw Ether**: To withdraw ether from the joint savings account, enter the amount and recipient address (one of the joint account owners) in the "withdraw" section. Click on the "transact" button to execute the transaction. The specified amount will be transferred from the joint savings account to the recipient address.

### 9. **Check Withdrawal Details**: After withdrawing, you can check the "lastWithdrawAmount" and "lastToWithdraw" variables in the "deployed Contracts" section to see the details of the last withdrawal.

### 10. **Repeat Steps 6-9**: You can repeat the deposit and withdrawal steps to interact with the contract further. The contract balance will be updated accordingly after each transaction.

### Please note that you're using the JavaScript VM in Remix, which is a local blockchain for testing purposes. Transactions and balances in the JavaScript VM are not actual Ethereum transactions, so you don't need real ether to interact with the contract in Remix. However, the contract functions and interactions work similarly to how they would work on the Ethereum mainnet or testnets.
---
## **Results**
### Below are the screen shots showing the application and results from executing the steps described above:  
### ***1. Contract Deployment***
#### Shows the Deployed Contract details in Remix.
##### ![contract_deployment.jpg](https://github.com/LUTOV001/20.CryptoSavings/blob/main/Execution_Results/contract_deployment.jpg)
#####
### ***2. Deposit***
#### Shows the results of depositing 300 wei in the account. Look the 300 shound under the `contractBalance` button on the bottom left.
##### ![deposit.jpg](https://github.com/LUTOV001/20.CryptoSavings/blob/main/Execution_Results/deposit.jpg)
#####
### ***3. Withdraw 10 wei***
#### Shows the update balance of 340 wei after the `transact` button in the ***withdraw*** section is pressed and the  10 wei amount shown is processed.
##### ![withdraw10.jpg](https://github.com/LUTOV001/20.CryptoSavings/blob/main/Execution_Results/withdraw10.jpg)
####
### ***5. Transfer 50 wei***
#### Shows the update balance of 290 wei after the `transact` button in the ***deposit*** section is pressed and the  50 wei amount shown in the `Value` section is processed.
##### ![transfer50.jpg](https://github.com/LUTOV001/20.CryptoSavings/blob/main/Execution_Results/Transfer50.jpg)
---
### **Credits**
#### Prepared by Luis Torres 
#### [LUTOV001](https://github.com/LUTOV001)
#### August 2023