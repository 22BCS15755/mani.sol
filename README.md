# solidity
  REQUIREMENTS
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

# Description
Details of the token:

tokenName: A public variable with the value "DOGECOIN" that holds the name of the token.
tokenAbbrv: A public variable with the value "DOGE" that holds the token's abbreviation.
totalSupply: Initially initialized to 0, this public variable tracks the total number of tokens available.
Mapping of Balances:

balances: A mapping that links individual token balances (uint) to Ethereum addresses (address). The number of tokens that each address has is tracked by this mapping.
Uses:

mint feature

The function generates new tokens and allocates them to a designated address.
Setting parameters
The Ethereum address to which tokens are to be minted is _address.
_value: The quantity of tokens to be struck.
Action: Adds _value tokens to the balance of _address and raises the totalSupply by _value.
burn function

The goal is to destroy tokens from a certain address.  
# Author
manikanta
