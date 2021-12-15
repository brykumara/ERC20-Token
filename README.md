# ERC20-Token
This is a submission I made for the individual coursework of COMP0163 Blockchain Technologies at UCL during the first half of my master's degree in November 2021. \
The task was to create a token with the following features:
1. Mintability: The token can be minted (increasing supply). Only a minter can mint the token and the original minter is the contract creator. A minter can transfer "mintership" to another address.
2. Burnability: The token can be burned (reducing supply)
3. Capped supply: The initial supply of the token at contract creation is 50,000, which is credited to the contract creator's balance. The total supply of the token is capped at 1,000,000.
4. Token transfer fee: A flat fee of 1 unit of the token is levied and rewarded to the minter with every transfer transaction ( mint or burn not included). A transfer transaction must be able to cover the transaction fee in order to succeed.
