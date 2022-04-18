# How to use

### Agenda

1. Planning
2. Metadata
3. Deploy your Contract
4. Mint NFTs



### 1. Planning

Please determine the following.

* Content of your NFT (e.g.)
* Chain
* Hosting location for metadata
  * Decentralized storage such as IPFS
  * Your own server
* Distribution
  * Airdrop
  * Sale on other markets such as OpenSea
  * Sale on your own webpage
* Royalty

### 2. Prepare your metadata

Prepare the metadata of your collection. We recommend this tool for a generative project!&#x20;

{% embed url="https://nft-inator.com" %}

For non-engineers, we also have a tool to create metadata from CSV.

[https://chocomint-deployer.vercel.app/metadata](https://chocomint-deployer.vercel.app/metadata)

* Please refer to the OpenSea standard to create metadata. [https://docs.opensea.io/docs/metadata-standards](https://docs.opensea.io/docs/metadata-standards)
* Work with a spreadsheet, etc., export the CSV, enter it in the text area, and press the DL button.
* Pair of attributes.$number.trait\_type and attributes.$number.value can create an attribute.

![](<../../.gitbook/assets/image (51).png>)

![](<../../.gitbook/assets/image (49).png>)

Upload the output metadata folder to IPFS.



### 3. Deploy your Contract

{% embed url="https://chocomint-deployer.vercel.app" %}

First, let's create a new contract.

![](<../../.gitbook/assets/スクリーンショット 2022-04-12 14.07.34.png>)

①Select Chain and hit Next button

![](<../../.gitbook/assets/スクリーンショット 2022-04-12 14.09.04.png>)

② Input contract name, symbol, and version.  If it is the first contract of your series, put 1.0.0 for contract version.

![](<../../.gitbook/assets/スクリーンショット 2022-04-12 14.15.54.png>)

③Input URL of the metadata. Don't forget to insert  "/" at the end.

![](<../../.gitbook/assets/スクリーンショット 2022-04-12 14.19.55.png>)

④Set the role for your NFT contract. Can set single owner(necessary) and multiple admin(optional).

![](<../../.gitbook/assets/スクリーンショット 2022-04-12 14.31.58.png>)

⑤ Connect Wallet and deploy the contract. Sign and send a transaction via MetaMask.

![](<../../.gitbook/assets/スクリーンショット 2022-04-12 14.34.25.png>)



### 4. Mint NFTs

※If you want to use lazymint, you need to skip this and deploy a sales contract.

This is for airdrop usage or sales on NFT marketplaces like OpenSea.



① Proceed to Mint page

② Create a CSV file with token ID and wallet address.

![](<../../.gitbook/assets/image (50).png>)

③ Input the CSV file, connect the wallet and send the transaction to bulk mint. Transaction will be split into 100 tokens each.

![](<../../.gitbook/assets/スクリーンショット 2022-04-12 14.49.35.png>)
