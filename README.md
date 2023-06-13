# Composable-DeFi-NFT-Bridge

Composable DeFi NFT Bridge is a smart contract that facilitates the transfer of non-fungible tokens (NFTs) between different addresses on multiple blockchains. It allows users to securely and efficiently move their NFTs, which increases liquidity and trading opportunities, liquidity mining, and participation in the DeFi space.

# This Smart Contract, named "Composable DeFi NFT Bridge," provides functionality to securely and efficiently transfer non-fungible tokens (NFTs) between different addresses on a blockchain.

# The contract offers the following features:

# Storage variables and mappings: The contract stores information about NFT owners and token balances for each owner.
# NFTMoved event: It is emitted when an NFT is moved from one address to another, enabling tracking of the transfers made.
# onlyTokenOwner modifier: It is applied to the moveNFT function to ensure that only the owner of the NFT can execute the transfer.
# moveNFT function: It allows the owner of an NFT to transfer it to a specific destination address, provided certain conditions are met, such as NFT ownership and timelock period.
# setTimelock and setApprovalLimit functions: These enable owners to set the timelock period for a specific NFT transfer and establish approval limits to prevent accidental loss of NFTs.
# getTokenOwner, getTokenBalance, and getApprovalLimit functions: Users can obtain information about the owner of an NFT, the token balance of an owner, and the approval limit set by an owner, respectively.

In summary, this Smart Contract provides infrastructure to facilitate the secure transfer of NFTs in the context of a Composable DeFi NFT Bridge application. Owners can transfer their NFTs with control and security, while additional features like timelock periods and approval limits are implemented to enhance protection and overall contract functionality.




