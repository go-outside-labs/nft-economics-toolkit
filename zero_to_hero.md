## NFTs: From Zero to Hero

<br>

#### nfts are cryptographic tokens that prove authenticity, ownership, and scarcity of digital assets.

<br>


> *a non-fungible token (nft) is a cryptographically secured token existing on the blockchain representing ownership of something unique. nft can represent tokenized ownership claims to real-world assets like a specific piece of land, or actual ownership of digital assets as in a rare digital trading card.uUnlike fungible tokens such as bitcoin where one btc can be exchanged for any other btc, each nft is completely unique and represents verifiable digital scarcity.*

<br>

#### what is fungibility?

* fungible goods are equivalent and interchangeable, like ether, bitcoin, fiat currencies, and voting rights.
* non-fungible goods are unique and distinct, like deeds of ownership, or collectibles.

<br>

#### what is a token?

* a token is a representation of something in the blockchain: money, time, services, shares in a company, anything.
* by representing things as tokens, we can allow smart contracts to interact with them, exchange them, create or destroy them.
* a token contract is an ethereum smart contract: "sending tokens" means "calling a method on a smart contract that someone wrote and deployed".
* a token contract is a mapping of addresses to balances, plus some methods to add and subtract from those balances. it is these balances that represent the tokens themselves. seomeone "has tokens" when their balance in the token contract is non-zero.

<br>

#### why nfts can power the future of commerce

* nft-enabled decentralized commerce could offer a viable alternative and save small businesses.
* non-fungibility itself allows for new kinds of transactions, where users are not limited to monetary exchanges, but can enjoy the exchange of assets (digital or physical).

<br>


#### blockchains 101

* whenever a node wishes to include a new transaction in the blockchain, it sends it to its peers, who then send it to their peers, and so on. in this way, it propagates throughout the network. 
* certain nodes, called miners, maintain a list of all of these new transactions and use them to create new blocks, which they then send to the rest of the network. 
* whenever a node receives a block, it checks the validity of the block and of all of the transactions therein and, if valid, adds it to its blockchain and executes all of said transactions. 
* as the network is non-hierarchical, a node may receive competing blocks, which may form competing chains. the network comes to consensus on the blockchain by following the "longest chain rule", which states that the chain with the most blocks at any given time is the canonical chain. this rule achieves consensus because miners do not want to expend their computational work trying to add blocks to a chain that will be abandoned by the network.

<br>

#### consensus protocols tl; dr

* **proof-of-work (PoW)**: used by bitcoin's protocol. Validate transactions to the miners, who are the nodes that solve cryptographic, or mathematical problems, using their computers. miners who solve a problem and validate and enable a block record are rewarded with bitcoin.
* **proof-of-stake (PoS)**: used by ethereum (after "the merge"). forgers (instead of miners) stake an amount of cryptocurrency, which allows them a chance, based on probability, to be a block validator. the successful forger receives the relevant block transaction fees as a reward. 
* **proof-of-authority (PoA)**: more centralized, it has predetermined block validators. new blocks on a blockchain are only created when the validators are in the majority. 

<br>


#### ethereum

* ethereum is a technology that lets you send cryptocurrency to anyone for a small fee.
* ethereum is an open-source, public, blockchain-based distributed ledger featuring smart contract (scripting) functionality. it enables developers to build blockchain applications with business logic that execute in a trustless environment, while leveraging the high availability of the ethereum network.

<br>

#### ether (Ξ)

* ether (ETH) is the cryptocurrency generated by the ethereum protocol as a reward to miners in a proof of work system for adding blocks to the blockchain.

<br>

#### accounts

* **user accounts**: create transactions, which must be signed using the account's private key, a 64-character hexadecimal string that should only be known to the account's owner (signature algorithm is ECDSA). 
* **contracts**: associated code and storage (the values of the variables at any given time). for instance, it might send ETH, alter its storage values, create temporary storage, call any of its own functions, call any public function of a different contract, create a new contract, and query information about the current transaction or the blockchain.

<br>

#### gas

* ethereum transaction fees: to transact on the network, users pay gas fees in ETH to miners running the computers that validate, or process, every transaction completed (from simple token transfers to more complex engagements with dapps). it's a unit of account within the EVM.
* this fee mechanism is designed to mitigate transaction spam, prevent infinite loops during contract execution, and provide for a market-based allocation of network resources.


<br>

#### references

* **[erc721.org](http://erc721.org/)**
* **[ef on erc-721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721)**
* **[ef on erc-1155](https://ethereum.org/en/developers/docs/standards/tokens/erc-1155)**
* **[what's ethereum](https://ethereum.org/en/what-is-ethereum/)**
* **[ethereum improvement proposals](https://eips.ethereum.org/)**
* **[scaffold ETH](https://github.com/austintgriffith/scaffold-eth)**
* **[eth gas station](https://ethgasstation.info/)**


<br>

---

### artist, creators, and collectors

> *the lesson of web 2.0: when the process of sharing content with others is owned entirely by private platforms, the cost of this mediation falls heavily on creators.*

<br>

* **[list of artists (compilated ~2021)](artists.md)**
  
<br>

#### example of collectibles

* **[cryptokitties](https://www.cryptokitties.co/)**: the first digital asset to use the ERC721 asset standard for nfts (in 2017).
* **[rare pepe wallet](https://rarepepewallet.com/)**
* **[bullrun babes](https://www.bullrunbabes.com/rules)**
* **[cryptopunks](https://www.larvalabs.com/cryptopunks)**
* **[curio cards](https://curio.cards/)**
* **[joy world](https://www.joy.world/)**


<br>

#### marketplaces

* **[zora protocol](https://zora.engineering/whitepaper)**
* **[known origin](https://knownorigin.io/)**
* **[foundation](https://foundation.app/)**
* **[nifty gateway](https://niftygateway.com/)**
* **[opensea.io](https://opensea.io/)**
* **[rarible](https://rarible.com/)**
* **[superrare](https://superrare.co/)**
* **[wax](https://wax.io/)**
* **[nonfungible.com](https://nonfungible.com/)**
* **[data.nyc](https://dada.nyc/artgallery)**
* **[maecenas.co](https://www.maecenas.co/)**
* **[portion](https://portion.io/)**
* **[meme factory](https://memefactory.io/)**
* **[beta.cent.co](https://beta.cent.co/~discover/)**
* **[async.art](https://async.art/)**
* **[token trove](https://tokentrove.com/)**
* **[cargo](https://cargo.build/)**
* **[blockparty](https://blockparty.co/)**
* **[ghost market](https://ghostmarket.io/)**


<br>

#### games and gaming marketplaces

* **[enjix](https://enjinx.io/eth/marketplace)**
* **[neon district](https://neondistrict.io/)**
* **[hedgie](https://www.hedgie.io/)**
* **[my crypto heros](https://www.mycryptoheroes.net/)**
* **[skyweaver](https://www.skyweaver.net/)**
* **[war of crypta](https://warofcrypta.com/)**
* **[,ine or die](https://warriders.com/)**
* **[world of ether](https://worldofether.com/)**
* **[axie infinity](https://axieinfinity.com/)**

<br>

#### monetization and indexes

> *protocols such as NFTfi and Rocket allow nfts to be used as collateral for peer-to-peer loans, enabling holders to treat their digital collectibles like any other asset to be monetized.*

* **[$whale](http://)**
* **[nftfi](https://nftfi.com/)**
* **[rocket](https://defirate.com/rocket-nft-loans/)**
* **[nf2/0](https://nft20.io/)**
* **[nfy](https://nfy.finance)**
* **[nftx.org](https://nftx.org/#/)**
* **[nftindes](https://nftindex.tech/en/index.html)**
* **[piedao](https://play-metaverse-token.piedao.org/)**
* **[indexcoop](https://indexcoop.com)**
* **[nft trader](https://www.nfttrader.io/)**


<br>

#### understanding assets

* **[nft market overview](https://nonfungible.com/market/history)**
* **[crypto slam](https://www.cryptoslam.io/)**


<br>

#### permanent storage solutions

* **[arweave](https://www.arweave.org/)**
* **[iPFS to arweave](https://ipfs2arweave.com/)**
* **[infinft](https://infinft.com/)**
* **[mintable](https://mintable.app/)**
* **[mintbase](https://mintbase.io/)**
* **[pinata](pinata.cloud)**

<br>

#### smart contracts

* **[smart contracts simply explained](https://www.youtube.com/watch?v=ZE2HxTmxfrI&ab_channel=SimplyExplained)**
* **[cryptopunksmarket solidity contract](https://github.com/larvalabs/cryptopunks/blob/master/contracts/CryptoPunksMarket.sol)**
* **[cryptocats contract](https://etherscan.io/address/0x06012c8cf97bead5deae237070f9587f8e7a266d#readContract)**
* **[creating a flexible NFT](https://kauri.io/#collections/Flexible%2C%20Upgradeable%20%26%20Highly%20Available%20NFTs/creating-a-flexible-nft-%28part-1%29/)**


<br>

---

### socioeconomics of decentralizing the world

#### communities

* **[peeps democracy](https://medium.com/peeps-democracy)**
* **[eth global](https://ethglobal.co/)**


<br>

#### opinionated articles 

* **[why people collect art](https://aeon.co/essays/what-drives-art-collectors-to-buy-and-display-their-finds)**
* **[some thoughts on token governance and curation](https://medium.com/knownorigin/some-thoughts-on-token-governance-and-curation-a-look-into-a-possible-future-for-knownorigin-41ac900f8a79)**
* **[can cryptoart really change the world](https://medium.com/knownorigin/can-cryptoart-really-change-the-world-54f26a4f2821)**

<br>

### decentralization

* **[why decentralization matters](https://onezero.medium.com/why-decentralization-matters-5e3f79f7638e)**
* **[progressive cecentralization](https://a16z.com/2020/01/09/progressive-decentralization-crypto-product-management/)**

<br>

---

### acronyms and concepts

* **dapps**: decentralized applications (which can include games, digital collectibles, online-voting systems, financial products and many others).
* **daos**: decentralized autonomous organizations (makerdao is an example).
* **defi**: decentralized finance: social currency backed by high-values assets.
* **dex**: decentralized exchanges ([uniswap](https://uniswap.org/) is an example).
* **liquidity pools**: pool of tokens locked in the smart contract, used to facilitate trade by providing liquidity, and used by some of the decentralized exchanges.
* **amms**: automated market Mmkers.
* **stablecoins**: offers users vital means of storing and transferring value on the blockchain, without exposing them to volatility.
* **chainlink vrf**: verifiable randomness function that allow developers to apply random traits to an nft.
* **minting**: creating of nfts (the process of validating information, creating a new block, and recording that information into the blockchain).
* **burning**: destructing a nft.

<br>

---

### hot wallets to get started

> *remember: not your keys, not your coins.*

* **[metamask](https://metamask.io/)**
* **[rainbow](https://rainbow.me/)**
* **[coinbase](https://wallet.coinbase.com/)**
* **[pillar](https://pillarproject.io/)**
* **[enjin](https://enjin.io/software/wallet)**
* **[trust wallet](https://trustwallet.com/)**
* **[exodus](https://www.exodus.com/)**

<br>

---

### general guides


* **[⭐️ ⭐️ ⭐️ ⭐️ ⭐️ - nfts skeptics guide](https://justincone.com/posts/nft-skeptics-guide/)**
* **[⭐️ ⭐️ ⭐️ ⭐️ - nfts players and landscape](https://coopahtroopa.mirror.xyz/PF42Z9oE_r6yhZN9jZrrseXfHaZALj9JIfMplshlgQ0)**
* **[⭐️ ⭐️ ⭐️ ⭐️ - opensea nft bible](https://opensea.io/blog/guides/non-fungible-tokens/)**
* **[⭐️ ⭐️ ⭐️ ⭐️ - cryptopedia](https://www.gemini.com/cryptopedia)**
* **[⭐️ ⭐️ ⭐️ - a beginner guide to nfts](https://linda.mirror.xyz/df649d61efb92c910464a4e74ae213c4cab150b9cbcc4b7fb6090fc77881a95d)**
* **[⭐️ ⭐️ ⭐️ - crypto makes the internet ownable](https://variant.mirror.xyz/T8kdtZRIgy_srXB5B06L8vBqFHYlEBcv6ae2zR6Y_eo)**
* **[⭐️ ⭐️ - nft beginner's guide](https://decrypt.co/resources/non-fungible-tokens-nfts-explained-guide-learn-blockchain)**
