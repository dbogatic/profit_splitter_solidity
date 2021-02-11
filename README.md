# Profit Splitter 

## Ethereum Smart Contracts with Solidity, Remix IDE, MetaMask and Ganache

![eth_stock_photo](images/eth_photo.jpg)
Source: [Pixabay](https://pixabay.com/photos/cryptocurrency-money-ethereum-3424785/)

This repo shows three examples of Ethereum Smart Contracts which were created in [Solidity](https://docs.soliditylang.org/en/v0.7.4/) programming language using [Remix IDE](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.7.4+commit.3f05b770.js/) and deployed via [MetaMask](https://metamask.io/) to [Ganache](https://www.trufflesuite.com/ganache). 
#

* [AssociateProfit Splitter](#associate-profit-splitter)

* [Tiered Profit Splitter](#tiered-profit-splitter)

* [Deferred Equity Plan](#deferred-equity-plan)

#
## Associate Profit Splitter


* This smart contract will accept Ether into the contract and divide the Ether evenly among the associate level employees. 

* It will allow the Human Resources department to pay employees quickly and efficiently.

* Once we created a contract in Solidity, we compile it and then deploy.

![compile](images/Screen_Shot3.png)

![deploy](images/Screen_Shot2.png)

* We verify in Ganache that contract has been created.

![contract](images/Screen_Shot1.png)

* Next step is to deposit intro contract 10 ETH which will be equally split between three selected Associates' accounts.

![deposit](images/Screen_Shot4.png)

* Finally, we verify that 10 ETH has been taken out of the sender's account (0x5DB....) and deposited into three split accounts (0x88c...,0xCfa...,0xF90...).

![previous_balance](images/Screen_Shot5.png)

![balance_after](images/Screen_Shot6.png)

#
## Tiered Profit Splitter

* This smart contract will distribute different percentages of incoming Ether to employees at different tiers/levels. 

* For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

* Same as in the previous example, we compile the contract in Remix IDE, deploy and verify in Ganache it has been created. 

![compile_tiered](images/Screen_Shot7.png)

![verify_tiered](images/Screen_Shot8.png)

* Next, we use the deposit function to add 10 ETH that will be distributed according to pre-set percentages to other three accounts. 

![deposit_tiered](images/Screen_Shot9.png)

* Lastly, we compare account balances before and after the deposit transaction.

![balances_tiered](images/Screen_Shot10.png)

![balances_after_tiered](images/Screen_Shot11.png)

#
## Deferred Equity Plan

* This smart contract will model traditional company stock plans. 

* It will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.

* As in the previous two examples, we create a contract using Remix IDE, deploy the contract, verify its creation in Ganache and finally test the share distribution function. 

![deferred_compile](images/Screen_Shot12.png)

![deferred_deploy](images/Screen_Shot13.png)

![deferred](images/ScreenShot14.png)

![contract_functions](images/ScreenShot15.png)

#
© 2021 Author: Dragan Bogatic





