---
home: false
title: "uns.network Tokens"
---

# The uns.network Tokens

<uns/> blockchain runs with a protocol token used to secure the network and to rewards network players. This is the “fuel” of the network. This is the `UNS Token`.

<uns/> blockchain works also with another token, a NFT Token representing @unikname Identifiers. This is the `UNIK Token`.

These two tokens are linked with smart-contract and their combination is the key concept of the Universal-Name-System. They ensure privacy and integrity of user’s registry and they're the key to provides universal DID Services such as new way of user's authentication and platform connections.

## The UNS Token

### UNS token is a protocol token

UNS token is a protocol token required to run the uns.network. Executing every <uns/> operation requires UNS Tokens: 
- to mint and sealed new @uniknames (UNIK)
- to update existing @uniknames (UNIK), eg. transfer ownership
- to update user’s registry
- to unlock <uns/> features 
- to extend capabilities/storage of Uses’ registry 
- to vote for Network Players
- ...

Some operations require to use a UNIK in addition to spending UNS.

### UNS Token Issuance

UNS Tokens are issued in two ways: 
1. UNS Tokens are minted by the protocol itself every 8 seconds for validation of block of transactions.
1. UNS Tokens are minted by the protocol for every UNIK Issuance. The number of UNS minted follow the Bitcoin Halving Process rule over the time, but rather than halving at some block numbers, it's halved at some quantities of UNIK supplied.

There is no UNS tokens at the initial stage of the network, but the genesis block have supplied 100000 UNS to enable start-up operations. These tokens have been allocated to wallet owned by the first network player : Unikname itself.

### Token name across networks: 

To prevent confusion and fatal errors, tokens are named differently between networks:
- SANDBOX : **SUNS**
- LIVENET : **UNS**

## The UNIK Token

### UNIK token is a NFT token

Every @unikname is secured by the blockchain. Once chosen, a smart-contract mints each human-readable identifier into the <uns/> blockchain as a NFT token. We name it the UNIK Token. 

There are as many UNIK tokens in the chain as there are @uniknames that exist.

UNIK tokens belong to the owners of Unikname crypto-account. The private keys enabling access to UNIKs are the private keys of Unikname crypto-account, so they're the same as the private keys enabling acces to UNS tokens of the owners.

The UNIK token is based on Ark Core technology, et more precisely on its NFT specialized fork, available in the Github's project [Ark Core NFT](https://github.com/spacelephantlabs/ark-core_non-fungible-token).
Ark Core NFT specifications are discussed in the standard _Ark Improvement Process_ and are available in their dedicated [AIPs issue](https://github.com/ArkEcosystem/AIPs/issues/70).

### UNIK Token remarkable properties

**Unique:** The owner of a UNIK has the guarantee that his identifier is unique and that no one can get the same within the same namespace. Every @unikname is represented by a single cryptographic hash code locked as a UNIK token within the <uns/> blockchain.

**Immutable:** Once created and sealed into the blockchain, the name can’t be neither altered, nor changed. 

**Obfuscated:** The internal string representing the @unikname identifier is obfuscated within the <uns/> blockchain. Thus, it can neither be read nor listed. Only people who knows it can make request on it.

**Self-Sovereign Asset:** Self-sovereign identifier is a concept where the individual or the entity has ultimate control over their identifier and is the final arbiter of who can access and use their data related to it. Every UNIK token has its ownership rules coded within the <uns/> blockchain smart contract. Only UNIK token owner has control over it.

**Created and obtained for Eternity:** Every UNIK token is minted and sealed into the <uns/> blockchain. No subscription plan required, nobody can delete it.

### UNIK Token Issuance

Only accredited nodes can mint UNIK in the chain. These nodes belongs to Network Players owning a `UNIK Factory Licence`, they're called `UNIK Factory Nodes` or simply `Factory Nodes`.
