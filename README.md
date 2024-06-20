# EVM-Subnet
--- 
## Overview

This project involves setting up and deploying a custom EVM subnet using Avalanche CLI, integrating it with Metamask, and deploying smart contracts using Remix. Below are the step-by-step instructions to achieve this, along with the tools required.

## Tools Used

- **Unix Computer** (MacOS or Linux)
- **Solidity**
- **Remix IDE**
- **MetaMask**
- **Web Browser**

## Step-by-Step Guide

### 1. Deploy Your EVM Subnet Using Avalanche CLI

- **Install Avalanche CLI**:
  Make sure you have the Avalanche CLI installed. You can install it using the following command:
  ```bash
  npm install -g avajava
  ```

- **Create and Configure Subnet**:
  Use the Avalanche CLI to create your subnet. Follow the official documentation or use the command below to create a new subnet:
  ```bash
  avalanche subnet create --name <subnet_name> --description "<description>"
  ```

### 2. Add Your Subnet to Metamask

- **Open Metamask**:
  Open your Metamask extension in your web browser.

- **Add Network**:
  Go to `Settings` > `Networks` > `Add Network`. Fill in the network details provided by Avalanche. These details typically include the Network Name, RPC URL, Chain ID, and Symbol. 

### 3. Make Sure It is Your Selected Network in Metamask

- **Switch Network**:
  Ensure that the new subnet is selected in Metamask. You can switch networks by clicking on the network dropdown at the top of the Metamask extension.

### 4. Connect Remix to Your Metamask

- **Open Remix IDE**:
  Navigate to [Remix IDE](https://remix.ethereum.org/) in your web browser.

- **Connect to Metamask**:
  In Remix, go to the `Deploy & Run Transactions` plugin. Select `Injected Provider` from the environment dropdown. This will connect Remix to your Metamask account.

### 5. Deploy the Smart Contracts

- **Write Your Smart Contracts**:
  Write your Solidity smart contracts in the `Solidity Compiler` plugin. Make sure to compile your contracts by selecting the appropriate version of the compiler.

- **Deploy Contracts**:
  In the `Deploy & Run Transactions` plugin, select your subnet network from the dropdown. Deploy your smart contracts by selecting them and clicking the `Deploy` button.

### 6. Test Your Application

- **Interact with Contracts**:
  Use Remix to interact with your deployed contracts. You can deploy tokens, create pools, and test various functionalities by calling functions on your deployed contracts.

## Conclusion

You have now set up a custom EVM subnet on Avalanche, integrated it with Metamask, and deployed your smart contracts using Remix. You can further extend your project by adding more functionalities and testing them thoroughly.

For any issues or questions, feel free to reach out for help!

## Additional Resources

- [Avalanche Documentation](https://docs.avax.network/)
- [Remix IDE Documentation](https://remix-ide.readthedocs.io/)
- [Solidity Documentation](https://soliditylang.org/docs/)

---

Happy coding! 🚀
