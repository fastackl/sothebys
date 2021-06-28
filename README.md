#KSPEC Highlights

#1. Identity
- Trace Suzy's identity vs try to trace timbl.eth (stops at Sotheby's)

#2. Robustness
- no single point of failure
- e.g. Kevin McCoy vs Timbl vs KSPEC

#3. Expressiveness & Completeness
- e.g. complete description of what the artwork is, cf what's only "referenced" in the NFT
- e.g. Sotheby's website mentions a 10% royalty, but that's not recorded anywhere in the NFT
- **Arbitrary number AND types of assets (live websites, source code, 3d assets, licenses etc.)**
- **Arbitrary number of platforms (e.g. Decentraland, Opensea, Snapchat etc.)**

#4. Extensibility
- ability to add information to the NFT, make it a living asset
- e.g. add versions compatible with new platforms, as they emerge

#5. Built-in permissioning for editing
- KSPEC edit permissions require a `selfTransferFrom` transaction from the creator 
- Permissions are at the blockchain level so everyone by default knows that a KSPEC transaction has received consent of both creator and the current collector
- Timbl left permissioning out of WWW when he wrote it, but KSPEC has a simple and unbreakable permissioning system out of the box

#6. Machine readability
- KSPEC provideds a standardised JSON data structure, easy for machines to read
- .e.g. references in KSPEC licence
- Data structure of most NFTs, including Timble NFT, Kevin McCoy etc. are heterogeneus and usually jam information into "description" and other fields

#7. Compatibility
- KSPEC is _just_ an ERC-721 / ERC-1155 transaction
- Hence KSPEC works with _any_ NFT contract
- Also works with any NFT, _even NFTs that have already been minted_

#8. Open source
- Free to use
- No intermediaries
- All you need is to be able to interact with the Ethereum

#9. Highly vetted, live and ready to go
- We've discussed KSPEC with the IPFS team, Superrare, Paul Chan, Pak, engineers and senior museum curators
- We're very confident at this point that it can't be broken
- already live with Suzy Treister's piece

#10. Standardisation
- Good prospects of becoming a widely accepted standard
- We're rolling KSPEC out to our K21 artists
- We're using our crypto and art institution networks to propagate KSPEC
- Low downside for anyone implementing it
	- no need to deploy a new contract
	- we are providing direct and hands on assistance to implement KSPEC to selected parties
	- no ongoing reliance on us - we will gladly teach anyone how to implement a KSPEC
- In parallel we are working on applications and APIs that automate KSPEC read / write operations and abstract away the complexity