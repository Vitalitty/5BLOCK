# 5BLOCK

## Background
You represent a company that needs to develop a smart contract for real estate sales.

Along this project you learn about create Solidity smart contracts on Ethereum. You also learn how to deploy and interact with them from a website.

In this topic we will call « tokens » the real estate managed by the smart contract.


## Instructions
The smart contract has to be deployed on Ethereum test network « Rinkeby ».

It will be necessary to develop a website for interact with contract. The connection and the various interactions must be able to be carried out with the Ethereum Metamask wallet.

On the homepage, we can see all the tokens created on smart contract. From the web interface, it can be possible for user connected with Metamask to create token.

A token has different attributes:
- a name
- an address
- a price (in Ether)
- one or several images

Note: Don’t hesitate to add more attributes to add realism to project.

From the web interface, the token owner can sell token or stop the sale.

It must be possible from the website to buy the tokens offered for sale by other owners. When the token is sold, it’s transferred to his new owner and the money from the sale is returned to seller.

At the sale of a token a 10% commission is paid to the contract. The owner of the contract can withdraw the funds from the commissions at any time.

The smart contract must be developed with Solidity, you are free to choose the language of website.


## Rendering
Students should include the following elements in their final delivery:
- Code project in zip archive
    - Smart contract code
    - Website code
- Technical documentation
- User documentation
 

## Bonuses
- The smart contract must be verified and published to https://rinkeby.etherscan.io/verifyContract (Connexions vers un site externe.)
- Tokens implements ERC-721
- It can be possible to edit token attributes
- The owner of the smart contract can change the amount of the commission
 

## Grades
The project will be graded as follows, on a 54/40 scale:
- Create tokens: 5 points
- View tokens: 5 points
- Buy a token: 5 points
- A commission is paid to Smart contract when a token is sold: 5 points
- The contract owner can withdraw commissions: 5 points
- Metamask Connection: 3 points
- Put a token on sale: 2 points
- Remove token from sale: 2 points
- Website design: 2 points
- Code quality: 2 points
- Technical documentation:  2 points
- User documentation: 2 points
- Bonuses: 14 points:
- Edit token attribute: 2 points
- Smart contract owner can change commission amount: 2 points
- Contract source code is published and verified on Etherscan: 2 points
- Token implements ERC-721: 8 points