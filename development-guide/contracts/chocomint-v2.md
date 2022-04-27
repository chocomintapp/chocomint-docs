# Chocomint V2

The GitHub repository for Chocomint v2 is not public yet. Please refer to etherscan below.

{% embed url="https://etherscan.io/address/0xB7d20474Fe31272a5794049d5D6057EE29cA04EC#code" %}

### Role Management

ChocoMintERC721 can hold two roles, Owner and Admin.

**onlyOwner**

* can set Admin

**onlyAdminOrOwner**

* can set and freeze tokenURI
* can set and freeze royalty
* can set and freeze provenance
* can set and freeze root

**onlyAdmin**

* can renounce admin role



### TokenURI

* **setTokenURIBase**
  * Set the base URI of metadata for the entire contract.
* **setTokenStaticURI**
  * Set the URI for a specific token.
* **freezeTokenURIBase**
  * Make base URI  unchangeable.
* **freezeTokenStaticURI**
  * Make the URI of a specific token unchangeable.
* **freezeAllTokenStaticURI**
  * Make all static URI unchangeable. After this, you cannot execute setTokenStaticURI.
* **freezeTokenURI**
  * Execute both freezeTokenURIBase and freezeAllTokenStaticURI.



### Royalty

ChocoMintERC721 supports the EIP2981 royalty standard. `function royaltyInfo(uint256 tokenId, uint256 value)` will return the royalty info of the token, thus, creators can receive the royalty when the token is traded on a marketplace that supports EIP2981.

* **setDefaultRoyalty**
  * Set the default royalty for the entire contract.
* **setTokenRoyalty**
  * Set the royalty for specific token.
* **freezeDefaultRoyalty**
  * Make the default royalty unchangeable.
* **freezeTokenRoyalty**
  * Make the royalty for specific token unchangeable.
* **freezeAllTokenRoyalty**
  * Make all token Royalty unchangeable.&#x20;
* **freezeRoyalty**
  * Execute both freezeDefaultRoyalty and freezeAllTokenRoyalty
* **royaltyInfo**
  * Returns the royalty of token If it is set. If not, returns the default royalty if it is set. And if nothing is set, returns zero address.

### Provenance

As with Hashmasks, you can set a provance to prove that the contents of the metadata have not been tampered with. [https://www.thehashmasks.com/provenance.html](https://www.thehashmasks.com/provenance.html)

* **setProvenance**
  * Set the provenance.
* **freezeProvenance**
  * Make the provenance unchangeable.
* **provenance**
  * Returns the configured provenance.

### Root

If the root is configured, you must always make a transaction with root and proof as a set.

* **setRoot**
  * Set the root.
* **freezeRoot**
  * Make the root unchangeable.
* **root**
  * Returns the configured root.
