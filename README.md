# SBML-Blockchain-Project  
A platform for displaying academic material and certificates as NFTs on the Ethereum blockchain
---
## Aproaches
### 1. NFT Aproach: Link permanently hosted documents through IPFS to a non-fungible token.
#### execution:
1. Create website which allows user to upload document to IPFS and gets the CID and generates a JSON file(URI) for the document  
2. Create a smart contract which verifies document author, mints an nft (passes in author wallet and link to URI)  
3. Website Displays Tokens owned by connected wallet.  
4. Website allows user to call function which assigns limited co-ownership to recipient (if document is some sort of certificate)

#### Pros:  
  - Permantently stored  
  - Unique  
  - Verifiable by uploader  
  - Decentralized verification (and possible encryption)  
#### Cons:  
  - Fees per token created (dependent on blockchain used)  
  - Ownership assignment fees (either to transfer token ownership or to give shared ownership)  

---
### 2. Tokenless Aproach: use IPFS for storage, and host server for encryption and verification
#### execution:  


#### Pros:  
  - Permanently Stored  
  - No fees  
#### Cons:  
  - Centralized verification and encryption  
  -
---
### 3. FT Aproach  
#### Pros:  
#### Cons:  
  -  

---
