# ETHAVAX4 Degen Token (ERC-20): Unlocking the Future of Gaming

DegenToken is a Solidity smart contract that represents a unique token with features such as minting, transferring, burning, and redeeming NFT accessories.

## Contract Overview

- **Name:** Degen
- **Symbol:** DGN
- **Decimals:** 10
- **Total Supply:** 0 (initialized)

## NFT Accessories

The contract comes with predefined NFT accessories:

1. **Excalibur**
   - ID: 0
   - Price: 5

2. **Muramasa Blades**
   - ID: 1
   - Price: 10

3. **Durandal**
   - ID: 2
   - Price: 15

4. **Goujian**
   - ID: 3
   - Price: 20

## Functions

### `storeNftAccessory`

Owner-only function to store NFT accessories with a unique ID, name, and price.

### `mint`

Owner-only function to mint new tokens to a specified address.

### `balanceOf`

View function to check the balance of a given account address.

### `transfer`

Function to transfer tokens from the sender's account to another account.

### `transferFrom`

Function allowing delegated transfers when approved by the token owner.

### `burn`

Function for users to burn their own tokens, reducing the total supply.

### `redeem`

Function for users to redeem NFT accessories by providing the accessory ID.

## Events

- `Mint`: Triggered when new tokens are minted.
- `Transfer`: Triggered when tokens are transferred.
- `Burn`: Triggered when tokens are burned.
- `Balance`: Triggered when token balance are checked. 
- `Redeem`: Triggered when an NFT accessory is redeemed.
- `Store`: Triggered when an NFT accessory has been created/stored.
  
## Getting Started
1. Copy and Paste the ETHAVAX4.sol to Remix(remix.ethereum.org).
2. Make sure that the Metamask wallet has sufficient AVAX balance and connected to the Fuji Test network.
3. Choose injected provider in the environment.
4. Compile and Deploy the ERC20 token contract to an Ethereum network using Remix.
5. Interact with the functions of the smart contract (check Functions or Usage).

### Usage
1. Mint new tokens as the owner using the mint function.
2. Burn your own tokens using the burn function.
3. Transfer tokens to another address using the transfer function.
4. Check token balance using the balanceOf function.

## Disclaimer
This ERC20 token contract is for educational purposes only. Use it at your own risk. The contract may have security vulnerabilities, and it is not recommended for deployment on the mainnet without proper auditing.

## Author

  - Mendizabal, Jed Marco
    - GitHub: @MarcoJSY
      
## License
 
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

