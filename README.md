## ETH project  
This project is made using using solidity.

## Description

- 'myproject' is our contract name
- In this we have created  3 public variables named : T_name, T_address, Total.
- T-name, T_address are string which are associated with token, and total is the total value that exist.
- Mapping function is used to map 'value' to a address , each address will have its certain value that can be altered using mint and burn -function
- 'mint' function is used to add value. It adds the value in both 'total' and 'address value'
- 'burn' funftion is opposite of 'mint' function. It is used to deduct values from both , if the amount entered is deductable , for which we used an if conditional 
   statement.


### Executing program

Clone the repository on remix ide.
Deploy the contract in Remix by compiling and then using "Deploy & Run Transactions".
Use the mint function with an address and amount to create new tokens.
Use the burn function with an address and amount to destroy tokens.
Check balances using the balances mapping and the total supply using the totalSupply variable.


## Authors
Lokesh Gupta
