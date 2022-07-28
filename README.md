At DLC.Link, we have a smart contract launched on Ethereum’s Kovan testnet. 
The purpose of this contract is to provide an interface to management functions for DLCs, and to track the status of open and historical DLCs. 
By doing these on-chain, rather than a traditional Web2.0 style API, our customers get the security and guarantees of leveraging blockchain technology.


The contract can be found on Kovan here https://kovan.etherscan.io/address/0x365441EC0974F6AC9871c704128e9da2BEdE10CE#code


The repo for the contract, with README, is here: https://github.com/DLC-link/dlc-solidity-smart-contract

## Task

We would like a web dashboard to view various information about the DLCs in the contract. Some parameters to report on the dashboard could be the following:
* The number of DLCs are being tracked by the contract
* The number of DLCs are currently open
* The age of the newest DLC
There are a few JS libraries to interface with a contract. Feel free to use vanilla JS or a web framework, as you prefer.
We would like to see that you can call the create-request dlc function on the contract, and show how your dashboard responds to the newly created DLC. 
Launch your dashboard somewhere so we can access it.

### Bonus
connect your dashboard to another contract that you launched, and track similar data there as well. 

### Hint
Consider using infura.com as an interface to Ethereum. 

