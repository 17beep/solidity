
# MyToken Smart Contract

## Overview
This project contains a simple ERC20-like token smart contract called **MyToken**, written in Solidity. The token's name is **Bea's Token** and its abbreviation is **MTK**. The contract allows you to create (`mint`) and destroy (`burn`) tokens, updating the total supply and individual balances accordingly.

## Features
- **Minting:** Create new tokens and assign them to a specified address.
- **Burning:** Destroy tokens from a specified address, reducing the total supply.
- **Token Details:** 
  - **Name:** Bea's Token
  - **Abbreviation:** MTK

## Requirements
- **Solidity Version:** 0.8.28 or higher
- **License:** MIT

## Installation and Setup
1. Clone the repository to your local machine:
   ```bash
  https://github.com/17beep/solidity/blob/main/beepsToken.sol
   ```
2. Open the project in your favorite code editor.
I would recommend using remix ethereum IDE.

## Usage

### Minting Tokens
Use the `mint` function to create new tokens and assign them to a specific address.

```solidity
function mint(address _addressTo, uint _value) public
```
- **_addressTo**: The address that will receive the newly created tokens.
- **_value**: The number of tokens to create.

### Burning Tokens
Use the `burn` function to destroy tokens from a specified address, reducing their balance and the total supply.

```solidity
function burn(address _addressFrom, uint _value) public
```
- **_addressFrom**: The address from which tokens will be destroyed.
- **_value**: The number of tokens to burn.


## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact
For any questions or feedback, feel free to reach out to the repository owner.
