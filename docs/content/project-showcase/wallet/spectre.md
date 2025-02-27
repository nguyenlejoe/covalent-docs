---
title: Spectre
order: 5
hidden: false
featuredImage: ../images/spectre.png
description: This wallets allows users to create multiple address and supports Fantom Opera Mainnet, Fantom Testnet, Kovan testnet and Ethereum Mainnet.
---

![Spectre Banner](../images/spectre.png)

&nbsp;

# Spectre

### Website

https://spectre.recurshawn.repl.co/

<Aside>

"Covalent API helped serve as an excellent resource for fetching data easily from the blockchain! We found the docs especially helpful and also the [How to guides](http://localhost:1313/docs/learn/guides) and [Tutorials](http://localhost:1313/docs/learn/tutorials) are great! The API itself is intuitive and we are looking forward to experimenting more with Covalent!"

</Aside>

&nbsp;

### Use of Covalent API

We have built an EVM compatible wallet from scratch using `ethers.js` and `crypto-js` for wallet creation and security.

This wallets allows users to create multiple address and supports Fantom Opera Mainnet, Fantom Testnet, Kovan testnet and Ethereum Mainnet. Users can track their wallet balances across the networks and also see their transaction history. Users can also send and receive ETH/FTM and other ERC-20 tokens. 

The wallet also features an explore page where users can search ENS names (only mainnet compatible) and addresses and view their NFT collection + token balances. 

We're using Covalent API to fetch crypto token balances and NFTs in the wallet itself and the explore page. We're also working on integrating Spiritswap data into the wallet so that users can keep track of token prices. We also intend to make the wallet a PWA.

&nbsp;

It uses the following Covalent API endpoints:
- [`Get token balances for address`](https://www.covalenthq.com/docs/api/#get-/v1/{chain_id}/address/{address}/balances_v2/) To fetch the address balances.
- [`Get transactions`](https://www.covalenthq.com/docs/api/#get-/v1/{chain_id}/address/{address}/transactions_v2/) To fetch all the address transactions.
- [`Get external NFT metadata`](https://www.covalenthq.com/docs/api/#get-/v1/{chain_id}/tokens/{contract_address}/nft_metadata/{token_id}/) To fetch NFT metadata.


&nbsp;

### Event

The project was built at [#OneMillionWallets - Fantom 2021](https://www.covalenthq.com/blog/omw-fantom-winners/)

&nbsp;

### Developers
- Shawn Pereira: _Discord - @recurshawn#0042_
- Salil Naik: _Discord - @SalilNaik#0786_
- Shrey Keny: _Discord - @Shrey#0749_ 