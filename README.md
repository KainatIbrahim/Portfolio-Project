# Portfolio-Project
# contract ERC20token1
# Declared state variables public
# used 2 mapping objects. "balances" and "allownce"
# "balances" a maping whose keys are of type address & values are type integer, used to store token balances
# "allownce" it includes all the accounts approved to withdraw from owner's acc + how many tokens to withdraw
# set the values of state variables in the constructor
# token1name: Token1
# token1Symbol: TK1
# token1TotalSupply=100;
# token1decimals = 18;
# Used a modifier names "onlyOwner" to set owner as the caller of fuctions
# Get the values of all state variables by making getter function--as they are internal
# function balanceOf: Returns the amount balance with address 'tokenOwner'
# function transfer: transfers amount of tokens 'token' from the function caller's acc to address 'to'
# And fires the transfer event
# function approve: owner approves delegate to withdraw tokens so that spender can withdraw tokens from function caller's acc. upto amount 'tokens'
# on success, must fire an event
# function allowance: get number of tokens approved for witdrawl.
# function transferFrom: It allows a delegate approved for withdrawal to transfer owner funds to a third-party account

# Finally deployed the contract through remix-Ethereum IDE to Rinkeby testnet. Further verified and published the contract.
