# ERC20-Token
This is a submission I made for the individual coursework of COMP0163 Blockchain Technologies at UCL during the first half of my master's degree in November 2021. The final grade of this coursework was 69, a merit classification.\
The task was to create a token with the following features:
1. Mintability: The token can be minted (increasing supply). Only a minter can mint the token and the original minter is the contract creator. A minter can transfer "mintership" to another address.
2. Burnability: The token can be burned (reducing supply)
3. Capped supply: The initial supply of the token at contract creation is 50,000, which is credited to the contract creator's balance. The total supply of the token is capped at 1,000,000.
4. Token transfer fee: A flat fee of 1 unit of the token is levied and rewarded to the minter with every transfer transaction ( mint or burn not included). A transfer transaction must be able to cover the transaction fee in order to succeed.

The token was then deployed on the Kovan Testnet. The following actions was also required: 

1. Deployed Smart Contract: 
  Link: https://kovan.etherscan.io/address/0x4372edeef7614fa633e8300cfc8de8fb0f9131cc 
  Hash: 0x4372edEef7614fA633e8300cFC8De8FB0f9131cC
2. Mint 60 new tokens to XYZ from Address 1:
  https://kovan.etherscan.io/tx/0x5ceface9e4dcbcf451c7901f045e12de6718890d4dbd4a9c9503b1fb410a1b50
3. Burn 70 tokens from address Account 1: 
  https://kovan.etherscan.io/tx/0x628812fdb3f4904d5e99cd64194c4a4c215b1d35240fcfbe5a86972eeb776b13
4. Approve address XYZ to spend up to 110 tokens from address Account 1:
  https://kovan.etherscan.io/tx/0x5ab6c5116735f5b8d79a362dbced02af9def21e08ea02fbf94afc0da1386b058#eventlog
5. Transfer mintership to address XYZ:
  https://kovan.etherscan.io/tx/0x537acdb602e41b66518fbf6e622db0c8ea39d6d01aa3311d00d4db7cecda57e4#eventlog
6. Transfer 40 tokens with address XYZ from Account 1 to a third address ABC:
  https://kovan.etherscan.io/tx/0x362255bdad70dc296fb02e18082e17f78165504d32a9b40a7dc43fe7ff51f901
  
Addresses:\
ABC: 0x9B410A850c8C03E8c945b3e3946F26bB953c1E0B \
XYZ: 0xA322298A9c3A15F00b7a4B0C30112c32Bb799E11 \
Account 1: 0x3f5875C4384d436Aff6BE3B2cc178AC7208183D6 
