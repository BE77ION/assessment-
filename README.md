# Project: Create a Token
In this we are going to create our own token ! well ,not really ,but kinda.

# Requirements
  1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

     # Getting started
     Take these actions to communicate with the Ember Token Contract:

1. Create an Ethereum development environment using an online Solidity IDE (such as Remix).

2. Make a new file, such as assessment.sol, and save it with the.sol extension.

3. Copy and paste the Ember Token Contract code that is provided into the document.

4. Click the "Compile" button after choosing the correct compiler version (such as pragma solidity 0.8.25) to compile the contract.

5. To deploy the contract, click the "Deploy" button after selecting the "Deploy & Run Transactions" tab and the EmberToken contract from the dropdown menu.

After the contract is launched, you can communicate with it by passing the required arguments when you call the mint and burn functions. Make sure you have enough Ether left over to pay the gas costs associated with carrying out the transactions.
