# Solana NFT Collection Mint Addresses

## About

This is a public repository containing the mint addresses of popular collections on Solana. Please add and help us expand this open source project.

This maps a collection name (e.g., `solana_money_boys`) to a list of mint addresses (e.g., `66MZJWWM7ucWay8R2BzYgZVQHo3X2ZviYvCi4BCr42u6`).

## How to Use

Pull and load the raw JSON file from this link: https://raw.githubusercontent.com/BL0CK-X/solana-nft-collection-mint-addresses/main/collections.json

## How to Help

You can help by providing the list of mint addresses for other collections on Solana to the `collections.json` file.

These endpoints might help you:
- Search Candy Machine: https://docs.blockchainapi.com/#operation/solanaSearchCandyMachines
- Get Candy Machine Metadata: https://docs.blockchainapi.com/#operation/solanaGetCandyMachineMetadata
- Search NFTs: https://docs.blockchainapi.com/#operation/solanaSearchNFTs
- Get a Candy Machine's NFTs: https://docs.blockchainapi.com/#operation/solanaGetAllNFTsFromCandyMachine
- List all Candy Machines: https://docs.blockchainapi.com/#operation/solanaListAllCandyMachines

You can find the candy machine IDs for collections in the file in this repository titled `all_collections_with_escrow_data.json`. 

You get an updated version of this data with this Magic Eden API endpoint: https://api-mainnet.magiceden.io/all_collections_with_escrow_data

Thus, you can help by getting the candy machine IDs of a given collection, along with the collection's name, and using our endpoints to pull its NFTs. We will do this too at some point, but you can also help here to move it along.

## Who We Are

We're blockchainapi.com. You check out our docs here: docs.blockchainapi.com

We make coding with blockchains easy. We have several functions relating to NFTs, candy machine, and NFT marketplaces. 

We have a repo of examples here: https://github.com/BL0CK-X/blockchain-api
