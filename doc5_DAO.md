we are going to expand our knowledge of Decentralized Autonomous Organization(DAO) due to decentralize lottlink governance and upgrade lottlink contracts and functionalities using DAO.


according to the chat gpt here is the steps to deploy 

1. Choose a DAO platform: There are various DAO platforms available, such as Aragon, DAOstack, and MolochDAO. Research and select a platform that aligns with your requirements.

2. Set up a DAO: Create an account or organization on the chosen DAO platform. This typically involves creating a wallet and configuring the necessary permissions and governance rules for your DAO.

3. Develop and compile your smart contract: Write your smart contract code in Solidity, ensuring it meets your project requirements. Use a development framework like Truffle or Hardhat to compile your contract code into bytecode that can be deployed.

here is the steps to deploy a simple contract using a DAO.

4. Prepare deployment parameters: Identify the constructor arguments and deployment parameters required by your smart contract. 

5. Fund the DAO: Ensure that the DAO has sufficient funds to cover the deployment cost. Transfer the required cryptocurrency or tokens to the DAO's wallet address.

6. Initiate a proposal: Depending on the DAO platform, you may need to create a proposal to deploy the smart contract. This proposal outlines the contract deployment details, including the contract address, bytecode, and any associated parameters. Follow the specific steps provided by the DAO platform to create and submit the proposal.

7. Community voting and approval: The DAO's members or token holders will review and vote on the proposal. The voting process can vary based on the platform and governance rules. If the proposal receives sufficient approval, it can proceed to the next step.

8. Execute the proposal: Once the proposal has been approved, the DAO platform will execute the proposal, deploying the smart contract to the specified blockchain network. The contract's address will be generated upon deployment.

9. Verify and interact with the contract: After deployment, verify the contract's bytecode and source code on a blockchain explorer or verification service. You can then interact with the contract using its address, either through a user interface provided by the DAO platform or directly through web3 libraries and tools.


And here is the steps to upgrade the contract using DAO:

1. Choose an upgradeable smart contract framework: There are several popular upgradeable smart contract frameworks available, such as OpenZeppelin, Hardhat Upgrades, or Truffle Upgrades. Select a framework that supports upgradeability and aligns with your development environment.

2. Develop and compile your upgradeable smart contract: Write your smart contract code in Solidity, making sure it follows the guidelines and best practices for upgradability. Use the chosen upgradeable smart contract framework to compile your contract code into bytecode.

3. Deploy the initial version: Use the upgradeable smart contract framework's deployment mechanism to deploy the initial version of your smart contract. This typically involves deploying a proxy contract that will act as a proxy for the logic contract.

4. Set up a DAO: Create an account or organization on the DAO platform of your choice. Follow the platform's instructions to set up the necessary governance structure and rules.

5. Prepare the upgrade proposal: Identify the new version of the smart contract that you want to deploy as an upgrade. Compile the updated contract code and gather the necessary parameters for the upgrade.

6. Create an upgrade proposal: Use the DAO platform's interface to create a proposal for the contract upgrade. Include details such as the new contract address, bytecode, and any associated parameters required for the upgrade.

7. Community voting and approval: The DAO members or token holders will review and vote on the upgrade proposal. The specific voting mechanism and rules will depend on the chosen DAO platform. If the proposal receives sufficient approval, it can proceed to the next step.

8. Execute the proposal: Once the proposal is approved, follow the instructions provided by the DAO platform to execute the proposal. This typically involves invoking a function on the proxy contract, instructing it to upgrade its logic to the new contract version.

9. Verify and interact with the upgraded contract: After the upgrade is executed, verify the bytecode and source code of the upgraded contract on a blockchain explorer or verification service. You can then interact with the upgraded contract using its address, either through the DAO platform's user interface or through web3 libraries and tools.






here is the outline of second phase:

1. which testnet is more supported in all dao dapps(tally, Aragon, DAOstack, MolochDAO, Colony, GnosisDAO)
2. deploy governance and token to the testnet
3. try deploy simple smart contract and call a write function
4. try deploy upgradeable smart contract using openzeppelin
5. deploy a new version of the contract
6. call the change implementation function in the proxy using DAO and governance.


https://www.alchemy.com/blog/types-of-daos

tally.xyz

tally : 
- could not sign in yet.
- still nothing about testnets

Aragon : 
- connected to wallet easily
- supports testnets(goerly, mumbai)
- supports mainnets(ethereum, polygon)

DAOStack :
- This app is undergoing maintenance right now. Please check back later.

Moloch :
- not realy interesting

ClonyDao :
- only gnosis chain

GnosisDAO :
- not for developers 