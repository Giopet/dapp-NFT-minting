# dapp-NFT-minting

## React App Setup

### Install Npm

Download and install Node.js from the official website (https://nodejs.org/).
Once Node.js is installed, open your command prompt (for Windows users) or terminal (for Mac and Linux users).
Verify that Node.js and npm are installed correctly by typing the following commands:

	node -v

	npm -v

If these commands return version numbers, it means that Node.js and npm are installed correctly.
If you need to update npm to the latest version, you can do so by typing the following command:

    npm install -g npm

This will install the latest version of npm globally on your system.

That's it! You have successfully installed npm on your system. You can now use npm to manage packages and dependencies for your Node.js projects.

### Create react app

Write a command using the CLI to create a react app: 

	npx create-react-app frontend

![image](https://user-images.githubusercontent.com/53083156/224837980-71dfe1d3-7c8c-4fe9-9a2b-4779c6f5d7e3.png)

## Wallet Setup

To download MetaMask, please follow these steps:
1. Go to the MetaMask website: https://metamask.io/
2. Click on "Download" in the menu at the top of the page.
3. Select the version that corresponds to your web browser. MetaMask is available for Chrome, Firefox, Brave, and Edge.
4. Click the "Add to Chrome" or "Add to Firefox" button to start the download process.
5. After the download is complete, open your web browser and click on the MetaMask icon in the top right corner of your browser.
6. Follow the instructions to set up your MetaMask account and create a new wallet.
7. Make sure to write down your seed phrase and store it in a safe place. This is the only way to recover your MetaMask wallet if you lose access to your device.

That's it! You are now ready to use MetaMask to interact with decentralized applications (dapps) on the Ethereum blockchain.

## Blockchain for developers

At the core of a blockchain is a cryptographic ledger managed by nodes which can be run on any computer, or by miners. It is these nodes that power the blockchain. Every transaction that occurs is stored and encrypted as a hash. These hashes are then stored in combinations as a block. Every node will then submit their block hashes to the network, and if they don't match that means they contain invalid ledger history, and are rejected and overwritten by the correct block. 

Blockchains that support smart contracts also store state data. The advantage to all of this is that these nodes operate independently, and effectively provide a hosted application environment that is completely distributed. This is what we're talking about when we talk about decentralization. Because these nodes are hosted by anyone anywhere, it means there's no central point of failure. For example, when China banned Bitcoin mining, the Bitcoin network didn't have regional downtime, it just routed transactions to the nodes that were still operating. This same system also provides redundancy.

Apart from transactions, other things happen on the blockchain that are done via smart contracts. This includes tokens, NFTs, blockchain data storage, complex transactions, and really just about anything you can come up with using smart contracts.

Everything that happens on the blockchain is public and immutable. This means that everything that happens including coding mistakes are all in plain sight. You can view things on the blockchain at [etherscan.io](https://etherscan.io/). And if you look at this website you can look up any address, transactions and see what's happened, and determine other things that are going on on the blockchain.

Blockchain technology is decentralized immutable, redundant, and public. It was created to handle transactions securely that can't be spoofed and on a network that isn't subject to outages.

## Decentralization and Web3 opportunities

DeFi (decentralized finance), tokenization, NFTs, DAOs (decentralized autonomous organizations), gaming applications, and other types of DApps (decentralized applications). 

Ethereum and other blockchains have standards to create your own tokens. This can be done for a variety of reasons, from awards to utility to governance, and is typically referred to as tokenization. Non fungible tokens or NFTs utilize tokenization, to make tokens not for spending but for tracking digital elements on the blockchain. These are often used for art but can also be used as access keys in many other use cases. 

Decentralized autonomous organizations or DAOs utilize the trustless nature of the blockchain to bring groups together to do a variety of tasks from investment groups to social groups to well, buying the US constitution. 

By using tokens or NFTs for access and enabling public voting on chain, you don't need to know people in the group to be able to trust in the process.

Many new play to earn games are arising where you can earn crypto from playing them. Additionally, in game items can be purchased and traded as NFTs. And there are even entire virtual worlds like Decentraland in what many are calling the metaverse. 

Blockchain technology is not only limited to cryptocurrency and non-fungible tokens (NFTs), but also provides a decentralized network that can be used to create various types of decentralized apps (DApps). These DApps eliminate the need for intermediaries, enabling users to perform financial transactions and other functions directly through the network. It transforms the way we interact financially and socially, a new internet is emerging that allows for the creation of innovative DApps, tokens, and NFTs.

### DeFi

Decentralized finance is the processing of financial transactions on the blockchain. It is is blockchain banking. DeFi apps range from lending DApps to ways to earn crypto through staking or liquidity pool farming. This can remove the need for a central resource or organization to handle the processing.

The general concept behind DeFi is that the current financial system sometimes called CeFi (centralized finance), forces us to rely on banks, insurance companies, escrow companies, brokers and central exchanges to invest, borrow, loan and make transactions. Ultimately, these institutions make considerable money, but provide little by way of service. The de-central and transactional nature of the blockchain opens up the opportunity to completely eliminate these institutions, and in turn, empower the participants to earn and save money. By empowering people for example, to make peer-to-peer loans, the interest earned by banks can now be earned directly by individuals, and the market will dictate the rates. 

Additionally, new options for collateralization, and trust make credit scores and similar tools unnecessary. Is is risky, but there are also high rewards. If you lend in cryptocurrency, you are inherently subject to the volatility of the coin you're lending. This could also be a risk as it could be more difficult for the borrower to return the payment. New lending models and methodologies evolve every day. So it will likely be that as this area matures there are options at varying levels of risk. Low risk options based on stable coins, and collateral or blockchain-based credit ratings, and higher risk options on more volatile coins, and higher risk borrowers. The options are bound for anyone looking to grow their income on the blockchain.

Many coins offer staking or stacking opportunities where your coins will be locked up for a set timeframe, and in return, you'll receive more of the same or related coins back. The amount varies on the coin, and often on the risk and volatility associated. 

Additionally, decentralized exchanges, and DeFi apps like Uniswap, Pancakeswap, Sushiswap and Alice, allow users to participate in swap fees by contributing to liquidation pools. They can even stake their liquidity stakes to earn more interest. 

Smart contracts lie behind all DeFi, executing transactions based on logic, not personal verifications. They are blockchain programming that can enable the blockchain to intelligently handle currency, holding currency from one wallet, releasing currency to another all through functions that are directly saved to the blockchain as are all of the transactions that they make.

DeFi provides a virtually unlimited way to do financial transactions. There are lending apps, ways to earn interest through staking and farming, and many more opportunities to disrupt the traditional centralized finance industry. 

Interest Models:
- Staking
- Yield Farming
- Liquidity Mining
- Decentralized Exchanges

### Tokens & NFTs

**Tokens** are the spendable or what we call fungible currency that can be created on a blockchain for a bunch of different use cases. 
**Non fungible tokens** (NFTs) use the same technology to enable people to exchange digital goods and more. 
 
Tokens on the blockchain come at two basic forms:
- Native currency of the blockchain, for example, ETH on Ethereum. 
- Custom tokens that are created through smart contracts. These custom tokens can be created to provide a number of different utilities from rewards in a network, devoting power to novelty like Doge. 
 
 The way these contracts work is they adhere to a specific standard. Now there are a number of different standards for tokens but the main one that we use is [ERC-20](https://ethereum.org/en/developers/docs/standards/tokens/). 
ERC-20 token specifies:
- how a specific tokens can work
- how you send them
- how you can manage events
- how you can do all kinds of things 

ERC-20 defines how a smart contract is written to dictate everything about a token: methods to send, how many tokens are in circulation, how they will be minted and more.

Anything you think would happen surrounding any kind of a token, it'll happen because of what's written in the standard. And if you look at the standard, you can see it's really just a number of methods and events that you implement. So creating your own token is simply a matter of creating a contract that implements these specific methods and events and does them in the way that you want them to. 
Many tokens that you've heard of are created using the ERC-20 token. These are all tracked on Etherscan. So you can actually go into Etherscan which is sort of the visualizer of the Ethereum network. And it will show you all the tokens, all the ERC-20 contracts that have been deployed on the Mainnet. And you can see a number of different tokens from stable coins to coins for different protocols to wrapped tokens and more.
 
  NFTs function in a similar way that ERC-20 tokens. And again, there are multiple contracts for these but the main one that people use is ERC-721. And this defines again how they're transferred and what happens. Now, NFTs often have additional functions outside of that original contract because they can be used for a number of different use cases. And additionally, because of their singularity and flexibility, these can be used to represent not just images, but also access tokens, other types of media, lottery tickets, domain names, and pretty much anything you can think of. So NFTs have become a real phenomenon for traders and a lot of projects have soared. It's funny, there's even new vocabulary that's come into our lexicon like aped in and that's what we call it when someone decides to buy an NFT, I aped in to some collection. 
  
  You can view all the projects that people see. The main marketplace is OpenSea. In OpenSea, you can go in here and you can browse the different types of NFT projects and you can look and there are different ones can purchase here and sell here and all that good stuff. So remember everything that happens on the Ethereum blockchain is public. So you can actually look at a specific wallet and here's a wallet. You can see what's in there, what tokens are, and you can even view the NFTs available in that specific token. Now in Ethereum, most wallets don't support NFTs per se. So you end up having to look at your profile in OpenSea or looking on something like Etherscan to see the tokens that you or someone else holds.
  
So all in all, tokens represent really the nouns of the blockchain. These are the things we can keep in our wallet, we can trade and spend. And tokenization is what brings all kinds of unique opportunities to projects. 

## Developer’s guide to Ethereum

Ethereum's a blockchain ,in a lot of ways, it's like Bitcoin in that anyone can download the software that you need to run the blockchain and you can even download a full node that has all the blocks of the blockchain and become part of the network if you want to.

### Ethereum virtual machine

What really sets Ethereum apart is the inclusion of the Ethereum virtual machine. This is what processes smart contracts. EVM is collocated with the blockchain processing software and client, so anyone who runs the client will also by default have the EVM installed. 
But the EVM is more than just the blockchain. It's also a state machine in that it can hold data beyond just currency and transactions. One way to think about it is it's like having an application stack. The Ethereum blockchain is the database, whereas the EVM is the app server that handles processing smart contracts and the programmatic functionality. 

So every Ethereum node or client runs the EVM, right? And this is how the entire Ethereum network works. With all these nodes running, it's constantly syncing the blockchain. That makes sure that there's consensus. If anyone tries to fake a transaction, for example, it will be rejected by the majority and get thrown out, and everything else will revert to the majority. So because of this whole network:
- There's fault tolerance, there's no downtime.
- The whole network itself is Ethereum. It's immutable because no one can change the data.
- It blocks censorship because as long as people are running nodes, there's always somewhere that your transaction can be handled.
 
So the EVM:
- Syncs the blockchain
- Processes the smart contracts.
- Stores contracts are stored in bytecode. So it's the essentially compiled application, not the source. And typically will use Solidity to write our smart contracts.
- The EVM has memory that it can use during processing. So it can do fairly complicated processing but that memory doesn't persist.
- However, you can save app data on the blockchain in key-value pairs.

[Ethernodes](https://www.ethernodes.org):
This website shows nodes and everything that are currently running. It tells us all about the Ethereum network. 
When you make a transaction, it will go out and make a transaction to some particular node of Ethereum, but then that will sync to other nodes.
So ethernodes shows you:
- The clients are being run. 
- The countries that clients are being run in.
- The sync status. How much of it is synced and how much of it is currently syncing in terms of the block.

[thviewer](https://www.thviewer.live):
It gives us a real-time view into what's happening on the blockchain. It shows different miners that are processing data and it shows you what's happening in terms of mining these blocks.

Types of clients that you can run:
- The execution client, which is the current consensus methodology, which is proof-of-work. That is the old-fashioned like Bitcoin way of mining using processing power. 
- The consensus clients, which is also called the beacon chain. It used to be called Ethereum 2.0. And this uses proof-of-stake. You can essentially lock up some of your Ether and that is essentially what will create new Ether in the mining process is these. Everyone's who's locked up their Ether will get rewards. 

There are a number of different clients out there and I won't get into them. Typically, most people, as you saw on that website use Geth, which is written in Go. But there are others for people who have preferences otherwise. 
The other piece to know about is you can run clients that are specifically for running testing. And they'll run in the Ethereum client locally. Ganache and Hardhat are testing environments that can be used for just this purpose. Additionally, there are other networks available in addition to the Mainnet that can be used specifically for testing. So they're kind of like somewhere between your local testing environment and the final Mainnet. 

So Ethereum is a blockchain for programming. And its core functioning is possible because of the EVM. And that's what processes are compiled smart contract. It's available in a number of different version but Geth is pretty much by far and away the most popular. Because Ethereum can process what we call Turing complete programming, which means it can do loops and iterate and things, it gives Ethereum a lot of power and make it a unique and really good platform for decentralized application development. 
