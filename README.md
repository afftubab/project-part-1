# ERC20 Token and Vault Contracts

This repository contains Solidity smart contracts for an ERC20 token and a Vault designed for managing the tokens securely. Below, you'll find details about each contract, deployment instructions, and usage guidelines.

## ERC20 Token Contract

The ERC20 token contract implements the ERC20 standard interface and provides basic functionality for transferring tokens, querying balances, approving spending on behalf of token holders, minting new tokens, and burning existing tokens.

### Functions:

- `transfer(address recipient, uint amount)`: Transfer tokens to a specified recipient.
- `approve(address spender, uint amount)`: Approve a spender to transfer tokens on behalf of the owner.
- `transferFrom(address sender, address recipient, uint amount)`: Transfer tokens from one address to another, given approval.
- `mint(uint amount)`: Mint new tokens.
- `burn(uint amount)`: Burn existing tokens.

## Vault Contract

The Vault contract serves as a secure storage solution for ERC20 tokens. It allows users to deposit tokens into the Vault and withdraw them securely. The Vault contract interacts with the ERC20 token contract to handle deposits and withdrawals.

### Functions:

- `deposit(uint amount)`: Deposit ERC20 tokens into the Vault.
- `withdraw(uint shares)`: Withdraw ERC20 tokens from the Vault.
- `totalSupply()`: Get the total supply of tokens held in the Vault.
- `balanceOf(address account)`: Get the balance of tokens held by a specific account in the Vault.

## Deployment Instructions

To deploy these contracts, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies.
3. Compile the contracts using a Solidity compiler.
4. Deploy the compiled contracts to your chosen blockchain network (e.g., Ethereum).

Ensure to configure parameters such as initial token supply, token name, symbol, and decimals before deployment.

## Usage Guidelines

Ensure proper access control and follow best security practices when interacting with these contracts, especially when handling large amounts of tokens.


## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using the ERC20 Token and Vault Contracts! If you have any questions or need further assistance, feel free to contact us. 
