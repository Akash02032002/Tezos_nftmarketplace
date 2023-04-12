# Tezos_nftmarketplace


# Mint It 

An **Mint It ( NFT Marketplace )** is a digital platform for buying and selling **NFTs**. This platform allow people to store and display their NFTs plus sell them to others for cryptocurrency or money.

## What are NFTs?
A non-fungible token is a unique and non-interchangeable unit of data stored on a digital ledger. NFTs can be used to represent easily-reproducible items such as photos, videos, audio, and other types of digital files as unique items, and use blockchain technology to establish a verified and public proof of ownership.

## Smart Contracts

- Minting tokens
- Transfer
- Adding operators

### Token Contract Address
```bash
 KT1KoBwe3dkoYRkEGnCs9sMfDNkwtLtjs4P8
```
### Marketplace Contract Address
```bash
 KT1MULmacoCxm2Wjb5ALKzYcJ65bazckUuJb
```

### Deployed Link
[NFT Marketplace](https://tezos-nftmarketplace.vercel.app/)

### Smart Contract Link

[SmartPy Contract]
## Demo

- Entering MetaData
![](https://github.com/figment-networks/learn-tutorials/raw/master/assets/Tezos-nft-marketplace-mint-nft.png)
- Listed NFTs
![](https://github.com/figment-networks/learn-tutorials/raw/master/assets/Tezos-nft-marketplace-show-nft.png)
- Minting NFTs
![](https://github.com/figment-networks/learn-tutorials/raw/master/assets/Tezos-nft-marketplace-show-detail-nft.png)

## Features

- **Complete Transparency**
  
- **Decentralization**

  
- **NFT’s Indivisible Nature**
  
  
- **Liquidity**
  
  
- **Authenticity and Unique Ownership**
  
- **High Level of Security**  

  ## Tech Stack

1. Front End / Client Side
    - ReactJS 
    - Bootstrap - CSS and other components
    - React-Redux for State Management    

2. BackEnd Server:
   - Smart Contract (SmartPy.io/ide)
     - Implemented a Token Contract to manage whole marketplace.
     - Implemented a Marketplace contract to mint and sell NFTs.
   
   - Axios
      - For internal API and smart contract calls.


3. Data Management (Databases): 
    - Hosted Smart Contract on Ghostnet.
## Getting Started


### Clone the project:

```bash
  git clone https://github.com/rajprem4214/Tezos-NFT-Marketplace.git
```

Go to the project directory

```bash
  cd Tezos-NFT-Marketplace
```

Start frontend server

```bash
 npm run start
```

#### Local Url for Server:

- Frontend is running on http://localhost:3000 
## API Reference

### Marketplace Contract

 A marketplace contract handles minting and managing the NFTs. We usually set this contract as admin of the NFT contract. Then we use inter-contract calling to mint, transfer, collect NFTs. There are some important features for a marketplace.
- Minting NFT
- Collecting NFT
- Transfering XTZ from contract to account. i.e. Collecting management rewards
- Updating admin
```bash
token: The address to the token contract.
```
```bash
metadata: Meta-data of this contract to make it recognizable in explorers.
```

```bash
admin: the admin for this contract,
```
```bash
token_id: we will use this to know the total number of NFTs we have minted.
```
```bash
data: This is a big map to save a particular token's data.
```
```bash
holder: The current owner of this NFT.
```
```bash
collectable: Whether the NFT is on sale or not.
```
```bash
author: The creator of the NFT.
```
```bash
amount: The amount at which this NFT will be sold, if the item is collectible
```





