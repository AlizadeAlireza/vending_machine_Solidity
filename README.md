building a donut vending machine smart contracr.

we are going to see how to deal with sending and reveiving ether to the 
smart contract.

we put money in and get something. simple financial transaction.

owner of vending machine collects funds and also restocks the vending machine.



1. declare state variables
    - owner -> the address of the person who deployed the contract 
    - donut balances -> the mapping type

2. functions:
    - purchase -> facilitate the purchase of a donut from the vending machine.
        is payable

    - restock -> to add more to the supply of the vending machine.

    - getBalance -> balance of the vending machine.
        getting total balance easily.

3. gas fee
    - each transaction in ethereum uses a certain amount of gas