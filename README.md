# Portfolio-Project
# Mintable Contract # 3

- contract ERC20token6

- Declared state variables public
- used 1 mapping object. "balances"
- "balances" a maping whose keys are of type address & values are type integer, used to store token balances
- set the values of state 3 variables in the constructor
- token6name: Token6
- token6Symbol: TK6
- token6decimals = 10;
- Used a modifier named "onlyOwner" to set owner as the caller of fuctions
- function balanceOf: Returns the amount balance with address 'tokenOwner'
- function mint: used to add tokens
- function transfer: transfers amount of tokens 'token' from the function caller's acc to address 'to' and amount of tokens
- function burn: takes 1 parameter as _token to burn the number of tokens which are being used. 

- Finally deployed the contract through remix-Ethereum IDE to Rinkeby testnet. Further verified and published the contract.
