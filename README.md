# ETH+AVAX Intermediate Assessment - 4

A Solidity smart contract to create an ERC-20 token called Degen (DGN) for a gaming platform, enabling minting, transferring, burning, and redeeming tokens for in-game items.

## Description

This project involves creating an ERC-20 token named Degen (symbol: DGN) for the Degen Gaming platform. The token allows for minting, transferring, burning, and redeeming tokens for various in-game items. The contract ensures that only the owner can mint new tokens, while any user can transfer, burn, and redeem tokens for items in the game store.

## Getting Started

### Executing Program

To deploy and interact with the DegenToken smart contract, follow these steps:

1. **Open Remix IDE**: Visit [Remix IDE](https://remix.ethereum.org/).
2. **Create a New File**: Click on the "+" icon in the left-hand sidebar. Save the file with a `.sol` extension (e.g., `DegenToken.sol`).
3. **Copy the Code**: Copy and paste the code from the [ETH+AVAX-Intermediate-Assessment-4.sol](ETH+AVAX-Intermediate-Assessment-4.sol) file in this repository into your new file in Remix.
4. **Compile the Code**: Click on the "Solidity Compiler" tab in the left-hand sidebar. Ensure the "Compiler" version is set to `0.8.20` or higher. Then click the "Compile DegenToken.sol" button.
5. **Deploy the Contract**: Go to the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "DegenToken" contract from the dropdown menu and click the "Deploy" button.

### Interact with the Contract

- **Mint Tokens**: Only the contract owner can mint new tokens by calling the `mint` function with the recipient's address and the amount.
- **Transfer Tokens**: Users can transfer their tokens to others using the `transfer` function.
- **Redeem Tokens**: Users can redeem their tokens for items in the in-game store using the `redeem` function by specifying the item ID and quantity.
- **Check Token Balance**: Use the `balanceOf` function to check the token balance of any address.
- **Burn Tokens**: Users can burn (destroy) their own tokens using the `burn` function.
- **Check Redeemed Items**: Use the `getRedeemedItems` function to see the items a user has redeemed.

### Modifications

No modifications are required for basic functionality. If you wish to expand the contract's capabilities or customize its functionality, you can modify the code accordingly.

## Authors

Parteek Batheja  
[@ParteekBatheja](https://github.com/ParteekBatheja)

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
