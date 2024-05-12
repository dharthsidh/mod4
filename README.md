# DEGEN Contract

This Solidity smart contract implements the ERC20 token standard with additional functionalities such as minting, burning, and redeeming prizes. Below is an overview of the contract functionalities:

## Contract Overview

### Features
- Minting new tokens.
- Burning tokens.
- Transferring tokens between addresses.
- Approving and transferring tokens on behalf of other addresses.
- Redeeming prizes based on token balances.

### Token Details
- **Name:** DEGEN
- **Symbol:** DGN
- **Decimals:** 18

## Functions

1. **Constructor**
   - Initializes token details like name, symbol, and decimals.
   - Sets the contract owner as the deployer.

2. **mint**
   - Mint new tokens and assign them to a specified account.
   - Only the contract owner can perform this action.

3. **burn**
   - Burn tokens from the caller's balance.
   - Requires a sufficient balance to burn.

4. **approve**
   - Approve a spender to spend a specified amount of tokens on behalf of the caller.

5. **transfer**
   - Transfer tokens from the caller's account to another account.

6. **redeem**
   - Redeem prizes based on specified choices.
   - Prizes are redeemed against token balances.
   - Available prizes are a diary, a T-shirt, a bag, and Dogecoin.

7. **transferFrom**
   - Transfer tokens from one account to another, with allowance checking.
   - Requires prior approval from the token owner.

8. **allowance**
   - View the amount of tokens that a spender is allowed to spend on behalf of a token owner.

9. **balanceOf**
   - View the token balance of a specified account.

## Usage

1. Deploy the contract to an Ethereum-compatible blockchain.
2. Mint initial tokens using the `mint` function.
3. Users can transfer tokens, approve spending, and redeem prizes based on their balances.
4. Token owner can burn tokens if needed.

## Disclaimer

MADE BY - SIDDHARTH BOYIRI
