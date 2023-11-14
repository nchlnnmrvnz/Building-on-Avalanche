# Building on Avalanche - ETH + AVAX

A metacrafters project for the ETH + AVAX module.

## Description

This project for Metacrafters consists of these 5 functionalities:
1. Minting new tokens: Owner must be able to create or min tokens.
2. Transferring tokens: Players should be able to transfer their tokens to others.
3. Redeeming tokens: Players should be able to redeem their tokens for items in the in-game store.
4. Checking token balance: Players should be able to check their token balance at any time.
5. Burning tokens: Anyone should be able to burn tokens, that they own, that are no longer needed.

The skeleton code can be found in this link: https://github.com/Metacrafters/DegenToken

## Getting Started

### Installing

* You can download the FinalAvax.sol file by clicking on it, and then clicking the download button found at the top right corner of the text file. The download button is beside the copy raw file button.

### Executing program

* Visit https://remix.ethereum.org
* Upload FinalAvax.sol using the upload files button above the folder named contracts
* Compile FinalAvax.sol in the Solidity compiler tab located on the left side of the screen. It is beside the Search in files button
* Click Deploy and run transactions button located below the Solidity compiler button on the left side of the screen.
* Under Deploy and run transactions tab, select FinalAvax.sol contract, input the initial supply and click Deploy
* Under the section Deployed Contracts, expand FinalAvax.sol
* Expand the burn, mint and transfer functions

After executing these steps you will now be able to use the program. You can check your total supply by clicking on the total supply variable and expanding its call in the terminal.
You will be looking at the decoded output variable to see the value of the total supply variable.
You can use the mint, transfer, redeem, burn, and checkBalance functions by placing an address, and an unsigned integer value as value in the function then clicking the transact button. However, only the owner can use the mint function.


## Help

Be sure to compile before deploying FinalAvax.sol </br>
Be sure to select FinalAvax.sol as the contract before deploying </br>
Only the owner can use the mint function </br>
You can use different accounts by expanding the account section under deploy and run transactions tab

## Authors

Nichole Anne Marie J. Avañez (avanez.nichole@gmail.com)


## License

This project is licensed under the Alan Gabriel Limyu License - see the LICENSE.md file for details
