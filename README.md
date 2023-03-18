# dapp-NFT-minting

## React App Setup

### Install Npm

Download and install Node.js from the official website (https://nodejs.org/).
Once Node.js is installed, open your command prompt (for Windows users) or terminal (for Mac and Linux users).
Verify that Node.js and npm are installed correctly by typing the following commands:
```console
node -v
node -v
```
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

To stop the server:
	
	ctrl + c

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

[Ethviewer](https://www.ethviewer.live):
It gives us a real-time view into what's happening on the blockchain. It shows different miners that are processing data and it shows you what's happening in terms of mining these blocks.

Types of clients that you can run:
- The execution client, which is the current consensus methodology, which is proof-of-work. That is the old-fashioned like Bitcoin way of mining using processing power. 
- The consensus clients, which is also called the beacon chain. It used to be called Ethereum 2.0. And this uses proof-of-stake. You can essentially lock up some of your Ether and that is essentially what will create new Ether in the mining process is these. Everyone's who's locked up their Ether will get rewards. 

There are a number of different clients out there and I won't get into them. Typically, most people, as you saw on that website use [Geth](https://geth.ethereum.org/), which is written in Go. But there are others for people who have preferences otherwise. 
The other piece to know about is you can run clients that are specifically for running testing. And they'll run in the Ethereum client locally. **Ganache** and **Hardhat** are testing environments that can be used for just this purpose. Additionally, there are other networks available in addition to the Mainnet that can be used specifically for testing. So they're kind of like somewhere between your local testing environment and the final Mainnet. 

So Ethereum is a blockchain for programming. And its core functioning is possible because of the EVM. And that's what processes are compiled smart contract. It's available in a number of different version but Geth is pretty much by far and away the most popular. Because Ethereum can process what we call Turing complete programming, which means it can do loops and iterate and things, it gives Ethereum a lot of power and make it a unique and really good platform for decentralized application development. 

## The DApp Stack

The stack is the combined tool set that's used to interact with the client, to handle data, to write and test code, and to do things that are specific to that environment. The Ethereum stack:
-  The **blockchain** is the root of everything and what makes decentralized applications possible.
-  The **wallet** provides a connection between the user, the UI of our DApp, and the blockchain, and it can do simple things like sending and receiving tokens directly.
-  The client side **JavaScript libraries**, which will handle interaction between the wallet and the blockchain on the client. The client side has pretty much settled to predominantly react.
-  The **smart contracts** when we want to do more complex interactions with the blockchain and with data. They can be called on by the JavaScript libraries and we'll talk directly to the blockchain.
-  Any sort of **file storage** that's decentralized is going to be handled by another service.

![image](https://user-images.githubusercontent.com/53083156/226069104-586715f1-527b-4887-9ff7-b167142bcee8.png)

Let's take a look at the details of today's ethereum full stack:
- The wallet is typically **MetaMask**.
- **web3.js** was the original JavaScript client library, and this is supporting interacting with the wallet and talking to the blockchain. However **Ethers.js** has evolved, and it's a newer library and it's a little bit smaller and more well documented, and even has some other benefits.
- Testing of smart contracts is typically done in **Truffle** if you're using web3.js suite, and in **Waffle**, which is new, and that goes along with the Ethers.js.
- When you want to interact directly with the blockchain, it used to be you had to run a node and really look through things quite manually. However, now there are a number of APIs available, including The **Graph**, **Alchemy**, **Morales**, **Infura**, and these have all made it a lot easier, not to mention we don't have to maintain nodes, they can maintain well performing nodes for us.
- The file system has settled to pretty much the interplanetary file system(**IPFS**) as the decentralized source of data. Swarm still exists, but most applications today in NFT projects tend to use IPFS for storage. And the arrival of pinata is a nice user friendly layer that sits on top of IPFS and makes it easy to interact with. 

![image](https://user-images.githubusercontent.com/53083156/226069592-dc63021b-6ba7-4b7f-8f67-1ad6a013a039.png)

## Wallets

The wallet is where users keep their tokens, both fungible and NFTs, but crypto wallets do more than that. The wallet is where the user experience begins and ends. For our dApps, we'll be interacting with these wallets either via mobile apps, or via web plugins.

There are many different [wallets](https://www.ethereum.org/en/wallets/find-wallet/) available for Ethereum. These wallets sometimes specialize in one thing or another, they might be an actual browser, a plugin, or an app.

There are networks on Metamask that you can use for testing: https://metamask.io/ -> Login -> Settings -> Networks.

On Metamask plugin you can show the network you are on and you can change it for testing reasons. Metamask plugin -> Ethereum Mainnet -> Show/Hide test networks -> Show test networks (ON).

![image](https://user-images.githubusercontent.com/53083156/225154760-9495b0eb-5ece-4960-9a5c-1a87c905a3aa.png)

## Smart contracts

At the core of what makes DApps work are smart contracts. Smart contracts are the programming classes of web three, and they're the backend and transactional layer of all of the decentralized applications that we build. 

Think of smart contracts as a special type of programming class that they have functions and variables. Some of the variables are built in, like those that store the ether within the contract.
Others are custom that you write yourself:
- public functions that could be called on from outside of the smart contract like from our DApp
- private that can only be called on internally within the smart contract.

Any of this data that's being stored in these variables or in the contract is written to the blockchain.

Smart Contract is a blockchain class.
![image](https://user-images.githubusercontent.com/53083156/225157938-af148d13-edc2-49f4-b8b5-a56aa4c6978b.png)

One big difference between this programming and other development environments is that calling write operations costs ether. We call this "Gas" because it's essentially fueling the blockchain. 
This can be a good thing because it essentially makes it expensive to write to the blockchain. So, it keeps junk from being written to the blockchain, which is good. It also pays the node operators for helping to fuel the Ethereum network, which is also good. 
However, on Ethereum, gas is very expensive. When you go to mint an NFT, for example, that's calling a smart contract. 

So, what's happening because of that is there are some layer two environments that are coming about that are built around Ethereum that essentially let you inter-operate with Ethereum, but the gas is paid on the other network. Additionally, some people are moving to some of the other layer, ones like Solana or Stacks.

Every contract runs in its own blockchain partition that's stored in an account, which is basically the same type of an account that would be a wallet address. And these smart contracts can hold tokens and they can release tokens when certain conditions are met, basically you have to call a function to get the data out.

![image](https://user-images.githubusercontent.com/53083156/225159556-545642f6-b818-470f-b02b-5ad3ce4a7e70.png)

One example is you could have a smart contract that holds money. So, when essentially you send money to smart contract, it gets held and when some conditions are met, then it releases the money to the other person. Once those conditions are met, kind of like an escrow, this is really how smart contracts began because it makes it easy for these financial contracts to be written up and essentially eliminate intermediaries. Basically we pay thousands of dollars to have someone escrow money for a house, which is really just this, only there's people monitoring it. But if you could automate it, that would be amazing. 

Smart contracts on Ethereum are stored as byte code on the blockchain. So, once you post your smart contract, once you publish it to the blockchain as this byte code so you can pile it and publish it, it is then in an address, now at that address, that smart contract can never be changed. It's immutable, just like everything else on the blockchain. So, if you do need to make an update in your smart contract, you have to create a new address and deploy it there. But, that old smart contract will still be there. You just might not be using it anymore, but that's kind of how it works. 

Some projects will actually expose the code of the contract so that people can see it and validate it and to be completely transparent about what's happening with the ether when it gets pushed to their smart contract. So, one key thing to remember is that smart contracts, even though there are decentralized app backend, they're also available publicly. So, someone can call on this. It's essentially like a public API. So, there's typically some way that you'll want to secure this. And one way to do it is to only allow it to be called from a single address or a certain subset of addresses. And this is one of the ideas behind white list minting. So, you have a special mint function that can only be called on by addresses that are in the white list. And then, only those people are allowed to mint that NFT, because keep in mind, NFTs are just a type of smart contract, as are ERC 20 tokens, so it's very important in Ethereum that you make sure your code is secure. 

Ethereum is Turing-complete programming language, everything is stored on the blockchain. So, it's decentralized, it's public, and unchangeable.
Smart contracts can do all kinds of financial processing and due to the fact that it's right into the blockchain, it costs gas. And of course it can hold data beyond just transactional and store that state. So, any key value pairs can be stored essentially in the blockchain, but every time you call the smart contract, that data will be available to the smart contract.

So, smart contracts are the programming classes that live on the blockchain, and they're what we use to be called on and operated with through our DApps. And it's really these smart contracts that give web three its core utility, and they're responsible for everything from tokenization to NFTs, to DeFi operations and more. 

## IPFS, Swarm, and Piñata

While Ethereum nodes host and provide the processing power for smart contracts, providing file storage to host client website files, NFT images and metadata, and other files that can support a DApp need a decentralized storage system. Otherwise, they'll be subject to the failings of centralization. This is where InterPlanetary File System, or IPFS, and Swarm come in.

In the beginning, Swarm was conceived as part of Ethereum. It was built for file peer-to-peer storage. It has since become a separate project. They even launched their own coin, BZZ. But it's still linked to Ether and the Ethereum network. It works, and it's still an active project, but it doesn't have the performance and scalability that IPFS has brought to the table. 

[IPFS](https://ipfs.io) has really become the standard for Web3. The reason why IPFS has this power and scalability is because it operates much in the same way that BitTorrent does. When you upload a file to IPFS, your file's broken up into smaller chunks and cryptographically hashed. When one IPFS node is asked for a file, it will search the network for another node who has that file available. Upon retrieving it, the node will then store that file for future use as well. 
Additionally, a node can pin files, meaning that each node contains the files that are most useful to it. New uploads of a file have a new CID (content identifier). This makes files resistant to tampering or censorship. So basically, like the blockchain, when you upload an image, it's immutable. It stays there. And if you want to change the image, you'll have to get a new CID, or content identifier, for that new updated image. So IPFS is fast and secure for storing and retrieving files. 

The problem with IPFS is that it's a programmatic operation and ultimately subject to the speed of the IPFS network, which is to say there's limitations. Pinata is a middle layer that makes it easier and faster to interact with IPFS, both for the creators of the application and the consumers of it.

Pinata provides a nice, friendly user interface for easy file uploading and also provides a fast retrieval. I think of it as like a CDN (content delivery network) for IPFS files.

Creating DApps often requires files outside of smart contracts. This might be the HTML, images and JavaScript of a website, or the media and metadata that's linked to an NFT. Either way, Swarm and IPFS offer solutions to store and retrieve these files. And Pinata provides a fast and easy method to upload and retrieve those files.

## Ethereum Naming Service

You may have seen some of these addresses, in people's Twitter handles. Drew.eth for example. Just as the domain naming service, or DNS, helps us to find websites on the web, ENS helps us to find resources on Ethereum. So ENS is its own project. You can register domains at [ens.domains](https://ens.domains/), domain website. When you register a domain, you'll receive an NFT, and that's stored in your Ethereum wallet. Now the ultimate in having a decentralized application, would be to host your website files in IPFS, and have them be discoverable via ENS. That way everything's decentralized. You never have to go to traditional internet network, to get data. If you hosted an app this way, it would effectively be hosted by the blockchain, which means it wouldn't exist at any IP address. And thus could be accessed by anyone, anywhere.

The way that ENS works is there is a single smart contract, that's the ENS registry. And that essentially stores all of the key information, about each of these names. Then these will link to resolvers, and the resolver essentially will determine, how it should be processed, and where to go to get the resource that you're looking for. 

The ultimate decentralized application, though not often realized, is to have everything from the location of the website, to the site's content, to the logic, and all the interactions, all stored on the blockchain. The only real way to do this is through ENS. This is a lookup system, similar to DNS, that maps to an easy to use name, like giopet.eth, with instructions on how to load the web files from IPFS. 

What do you have to do in order to resolve your dApp via ENS?
You will need to use javascript libraries like Fleek to ensure ENS is used.

## Architecture of the DApp

![image](https://user-images.githubusercontent.com/53083156/225164875-f0d88a6b-6e94-4407-9d08-9b3bf9d8d5f5.png)

The front end will be React, JavaScript, HTML, and CSS, like pretty much any Web 2.0 site. We use JavaScript libraries to talk to the blockchain, which is Ethers.js.

The web files and assets can be hosted on either IPFS or traditional web hosting environments, AKA, we'll just call it the cloud.
Keep in mind that if you're hosting solely on IPFS, then you'll need to have the site available via the Ethereum Name Service (ENS), and you're going to have less control over performance and latency. But it will be more decentralized. A site hosted in the cloud is subject to the normal issues of centralization, which is it can be hacked, it can be DDoS-attacked, and generally speaking, it's more centralized. So it can be blocked as well.

We'll use a smart contract to generate our NFTs. There are many uses for smart contracts, but the minting and handling our NFT transactions, the actual NFT contract will be the main one that we use for this particular dApp. 

These will then be deployed to Ethereum and they will be deployed out towards the entire Ethereum blockchain. 

We'll store the images and metadata for our NFTs on IPFS. This will provide a nice decentralized storage mechanism that's secure, each will be uniquely identified, and there's assurances to anyone who's buying our NFTs that we can't change them because the CIDs will be contiguous.

We can also read from the blockchain, if we want to, using third party APIs, like Infura, Alchemy, and The Graph.

## DApp Back-End

### Introduction to Solidity

Solidity is a language that was created specifically for writing smart contracts. It's a pretty young language, having been first proposed in late 2014 and then later integrated into the Ethereum project. It's ECMAScript based and very similar to JavaScript in syntax. It's influenced by C++ and Python as well. It works by running in the Ethereum virtual machine.

When you compile it, it will be saved to an address on some Ethereum network, either to local testing network or one of the public testing networks or the Ethereum mainnet, depending on where you want to save it.

Your DApp, you're going to be calling most likely, on these contracts from JavaScript. So you can hide that from the user for the most part. They won't actually see which contract you're pulling from. However, it will be technically a different contract. So if you change the NFT contract, it will actually be a different NFT, right? So because of this, it's very important that your code is well thought out and well tested before you publish to the main net. It's also common, even though the bytecode is all that gets published to the network. It's often quite common to publish the source code as well along with it and there's a place to do that.

Solidity is statically typed and supports inheritance. It's very object oriented. It has a lot of built in functionality to support elements of the blockchain and abstract a lot of the cryptography that happens behind the scene. So you don't have to actually learn how that all works. The docs can be found at soliditylang.org.

Any function that writes to the blockchain is going to cost gas, right? So if I read, no problem. That is free externally. But if anything happens, it will be processed and gas is processed in wei, W, E, I. And wei is the smallest unit of Ethereum that you can have, down to the last decimal point, basically, in eth. So oftentimes you'll see numbers are written in those sort of forms, and you'll have to decode how many eth that is by figuring out how many decimal points to add.

There are a number of key concepts to remember. Storage, blockchain versus memory, right? Remember, things will be stored on the blockchain. They'll exist in memory very shortly, but they'll eventually be saved in the blockchain. A lot of the things that will be stored within your smart contract can be accessed.

### IDE

[Remix](https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.18+commit.87f61d96.js):
Exists both online and in a desktop application.

### Testing

[HardHat](https://hardhat.org/) is a super helpful tool for testing and deploying DApps. It provides everything you need to compile, run tests and deploy our smart contracts to the blockchain without having to think about all of the underlying things like Waffle and Ethers.js and all that good stuff. 

### OpenZeppelin contracts

For certain types of contracts, we have the advantage of using pre-built and pretested smart contracts from [OpenZeppelin](https://www.openzeppelin.com/).
OpenZeppelin is an open source repo essentially of tested smart contracts that can be reused and is a great starting point. And sometimes for very simple things, it can be the start and endpoint. It can be the actual solution.
So for our NFT, we're going to create a smart contract that implements the ERC 721 standard. This is the core implementation for NFTs and it's going to handle the minting, transferring, and other key functions of the NFT, and this contract will be the heart of our NFT. 

#### Installation (backend-dapp)
	
	cd backend-dapp
	
	npm install @openzeppelin/contracts
	
	npx hardhat
	
	code .

### Creating a mint() function

DappNFT.SOL

### Deploy smart contracts with Hardhat

We'll need to deploy it to a network so that we can interact with it and test it.
In our contracts folder, we have our NFT contract that we created, and we also have this Lock.sol, and this was part of the project that got created with Hardhat.
And we're going to use Hardhat for deployment. Notice it also creates a sample script (deploy.ts). Now this script is really the deploy script. So this is what's going to do the deploying, and this one is built for that Lock.sol, but it's nice because it gives us an example that we can utilize. And it's going to deploy based on how we configure it in the Hardhat config file (hardhat.config.ts). 

So the first thing we're going to do is we're going to change our Hardhat configuration so that it's set up for how we need to deploy it.
I just want to change the solidity version to 0.8.9, just because of how we had set it up (in DappNFT.sol also).
We create a new script called mint-script.js (to do the deploy), and we can delete this old script 'cause we don't need it anymore, and we could actually delete the Lock.sol as well.

Deploy command:
	
	npx hardhat run scripts/mint-script.ts

It gives you the address. And this is the address in the local server that comes along with Hardhat. So we have our NFT smart contract.

### Testing with Hardhat and Waffle

Hardhat has a couple of ways you can test:
-  If you're using Ethers.js, you can use Ethers.js and Waffle, which is the testing environment.
-  If you're using web3.js, you can use web3.js and Truffle. 

Now, regardless of which one you're using, behind the scenes, it's going to be using [Mocha](https://mochajs.org) (is used also in Node.js) and [Chai](https://www.chaijs.com/). Chai is what we use for our assertions, basically, just to test equivalency.

Go into testing environment (test folder) and delete the old file (Lock.ts) and create a new file mint-test.js.

Run the tests:

	npx hardhat test
	
### Deploying NFT Metadata with Piñata

A best practice for NFTs it's to deploy your images and your information about the NFTs, like traits and things like that, called metadata, in a decentralized fashion. Now, there are ways to put these directly in the smart contract, but it's a fairly common practice to use IPFS to do this.

By keeping your NFT images and metadata decentralized, it instills trust in your NFT project. If you were to have this at a domain location, technically, you could shut down your server, and then all of the images related to the NFTs would be gone. This is what we call a rug in the NFT world and obviously, it's a bad thing. 
 
So we use [IPFS](https://ipfs.tech/). IPFS is short for InterPlanetary File System. It's basically network file storage that's decentralized. I like to think of it as AWS S3, but on blockchain.

[Pinata](https://www.pinata.cloud/) is a service that provides a simple interface to make it easier to interact with the IPFS, both through the web interface that they offer, but also through an API. 
 
When you log in, you have your files, your gateway, and then you can verify CIDs to see what files they link to. So when you upload a new file, it will then create a CID, which is a content identifier, and this is what we use to refer to either the metadata or the image itself.
When we get this, we're going to do the metadata. So what we're going to do is we're going to upload our file to Pinata, our image, and then we're going to add that to the metadata, and then we're going to upload the metadata, and the metadata will then be what we use for our token URI when we create a new NFT.

So let's go ahead and select a file (for our NFT) and if I click on this, it will let me view. So it's uploaded and you can see the content identifier.
So I'm going to copy that, then I'm going to go into VS Code, and I'm going to open my metadata file and I'm going to add a content identifier (instead of CID on "image": "ipfs://CID") and put a json extension on the file.
I'm going to go back into Pinata, and I will upload my metadata file and you notice I also had some other information describing it.  These are the metadata standards that they keep at [OpenSea](https://docs.opensea.io/docs/metadata-standards) and you can see how, inside of here, there's a particular way that we define everything. 
You can add your own properties if you want to. That's the beauty, and those might have to do with the type of utility that you're offering.

Metadata format example:
```json
{
  "description": "I love dapp.", 
  "image": "ipfs://QmRdGz3WRZz7JSLwE74RsxauRuon5snjoBZ8kjgHReAD47", 
  "name": "Screenshot 2022-02-19 190829",
  "attributes": [], 
}
```

Now that we've got it uploaded into Pinata we can take this data, and we're going to use that data as our token URI that we will use to set up our NFT.
So we learned in this unit that the key information of NFT is stored by the token URI, which is the metadata, and that will include a link to the image, which should also be stored in Pinata. It's best practice to host these in a decentralized fashion and using IPFS and Pinata can really help make this process easy. Once we've done this, then we're ready to start building the front end of our minting.

## DApp Client

### Introduction to ether.js and web3.js

Once you have your smart contract ready, you'll need to connect the UI of your DApp to the blockchain. This connective tissue is done using one of two JavaScript classes, web3.js or ethers.js. 

Web3.js:
- It is the OG( Original Gangster) of Ethereum web DApps.
- It was originally created by the Ethereum Foundation. 
- It's the oldest library 
- It has the most contributors of either project. 
- It has one single interface for interacting with the blockchain. 

Ethers.js:
- It was created and is maintained by Richard Moore about a year after Web3.js was created. 
- Now this library has grown a lot in popularity, partly because it's a bit lighter weight, another because it has two separate interfaces, one for the provider, which also gives you the ability to connect through different APIs instead of just connecting to the Ethereum testnets and Ethereum Mainnet. And then it also has the Signer, which is how you connect to a wallet when you need to send a private key and things like that. 

Both of these are great projects, and neither is the wrong choice. Web3 is still very popular. I chose ethers.js for this project because it seems to be trending towards the lead. In addition, it also supports out of the box Ethereum Naming Service (ENS). 

Go to frontend folder and write the command:

	npm install ethers
	code .
	
All the stuff is happening in the Navibar.js file and then we need to import ethers: 
```javascript
const {ethers} = require("ethers");
```

###  Authenticating users with MetaMask 

https://docs.ethers.org/v5/api/

Let's look at how we can use it to build out our DApp and talk to the wallet. With [ethers.js](https://docs.ethers.org/v6/api/) there's two key interfaces, the provider and the signer.
The provider is the main methodology through which we talk to the blockchain and its creation can help to determine how we want to talk to the blockchain. 
By default it's going to talk to the mainnet, but we can set it for one of the test nets or localhost or using an API like [Infura](https://www.infura.io/) or [Alchemy](https://www.alchemy.com/).

There are a number of different providers depending how you want to connect. We're actually going to use the [Web3Provider](https://docs.ethers.org/v6/migrating/#migrate-providers) or [BrowserProvider](https://docs.ethers.org/v6/api/providers/#BrowserProvider) in ethers 6.1.0. 
It allows you to talk to MetaMask and use MetaMask objects. So that way we're going to be talking to the provider through the wallet and through what's being injected by the wallet. And it allows us to have control in a development environment by changing the network.

By using any of these providers you can do whatever you need in the blockchain, such as:
- Get whatever information you want: balance of any account, addresses, blocks, transactions.
- It supports ENS, so if we want to look things up, or we can just actually pass addresses as ENS addresses, and it will actually find out what the actual address is.
- It can get us signers. And once we get a signer, that's our connection to the wallet, which is going to issue the private key. Now we need that connection in this instance because when we call the mint function, the users going to have to sign it by their wallet and pay for gas when they mint.

_(navibar.js) So, let's go back into our code, and let's have a look at what we've got. So a few things we're going to need to change. For one is originally our NFT button just said mint now. So now we want it to actually either say mint now, but only if we've connected the wallet. Beforehand, we want it to say connect wallet. So we're doing some checking, and you can see this isConnected, is available to us now because we've imported state from react, the useState, and we've also created this variable isConnected, right? And that's going to use state. So we've got that all set up. Then we have our handleButtonClick. So when the user clicks the button, depending on whether it's connected or not, it's either going to connect the wallet or mint the NFT. So that's that. When we go to connect the wallet, so the first time you connect, remember, it's not going to say mint, it's going to say connect wallet. Now when you go to connect wallet, the handler's going to be this connectWallet function. Now in this function, the provider is being set. So that's our global variable we've created here of the address of the signer and the provider. The provider's being set to the result of instantiating a Web3Provider and passing our window.ethereum object, which we're getting from MetaMask. Then we're going to get the signer and set that to the signer value. And finally, we're going to set the address to the address of whatever address the signer has chosen, the wallet has chosen, and that will call the setAddress function. The setAddress function is just a simple function that sets the address based on what's passed, and it's going to log to the console and also toggle isConnected. So all these things are happening. You can see our mint NFT is empty. We'll get to that. But for now we just want to connect the wallet. So let's go ahead and go back to our browser, and let's open our DApp at localhost 3000. So here we are. Now, I like to turn on my console so I can see what's going on. Now, when I connect wallet, it opens MetaMask. Now, if I'm not logged in, it might prompt me for a password, but I am logged in, so I can go ahead and do that. And I can select which address I want to connect with, connect, and you can see it tells me that it connected and what address, I click OK, and you can see that it changes to mint now. So now I'm ready. I've set my address for my account, and I'm ready to get started minting my application. So now that we've got this in place, let's look at how we can interact with the blockchain using that provider object. _

### Getting blockchain data 

Now that we've made our wallet connection, we're ready to do some blockchain interactions with our DApp.
In order to interact with the blockchain in terms of how we want to do it, let's go ahead and start our local node. That'll allow us to get some ETH and do things that we wouldn't do unless we had a ton of ether on the main net.
So I'm going to go to the terminal and I'm going to create a new window. I've got my DApp(frontend) running in one window. And in my second window, I'm going to go into the back end of my DApp.
	
	npx hardhat node

And this will actually fire up a local node of Ethereum through Hardhat. And we can actually talk to it. Once it connects and establishes it, it's going to show us a bunch of accounts. Each of these accounts, have 10,000 ETH already assigned. So I'm going to copy private key. And then I can go back to my browser and I can go to my wallet. Now, the main thing is I need to be able to make sure that I can connect to the local test net.   

Now I go to add our local network. So I go to Networks, and I'll create Add a network and we'll call it localhost. It's localhost:8545. And the chain ID is going to be 31337. And then the currency symbol is going to be ETH. Import Account, and then select type, Private Key. And then I paste my private key, and I say Import. So now, I've got my 10,000 ETH that I could start playing around with this at my localhost. 

When you look at the Providers, you can get balanced from an address, get blocks, get transaction counts from a specific address. There are a lot of things that I can get from the blockchain. If we want to get more information about wallet, we're going to have to go into the Signer to connect. So one of the things you can do is I can go and see if there's enough ETH in someone's wallet before they mint. In this case, our particular minting object, it's free. So we don't have to worry about that. But if you are minting something for, say, 0.2 ETH or 1.6 ETH or whatever it is, you might want to check and make sure that they have that balance before you call the mint function because it won't work if they don't have enough money. 

In the code: In my wallet connection, I'm going to go ahead and take a look at the balance. I'm going to create a little variable called balance, and I'm going to say let that equal to signer.getBalance. So that then is going to get the balance from the address that's connected. 
Now I'm going to go ahead and type in console.log. 

Actually, what I want to do is I want to view JavaScript Console, and let's go ahead and take a look. When it connected to 2266, it has this big number. And look at the value, it's in hex. So when you transfer amount of ether inside of Ethereum, it is going to be in wei, which is the smallest unit you can possibly use, which is 18 decimal places to the right of one ether. So 10,000 ether is quite a lot in terms of how many wei, so we need to convert it. And it's also in base 16, which is not really how the human brain works. So we can actually use some utilities to translate this. We have this one called [formatEther](https://docs.ethers.org/v5/api/utils/display-logic/), which will change it to ETH. So it'll be a decimal point to tell me 0.00, whatever ETH. Now in this case, it'll be 10,000. 

I'm going to go back into my code. And instead of logging the balance, I'm going to await, and I'm using this because it's asynchronous call, because I actually need to go out and I need to format it using the ethers library. So ethers.utils and then formatEther and then make sure I get this. 

Let's go ahead and go back and refresh our React App. Now we'll connect our wallet And you can see it outputs 10,000. And that's what it read from the wallet which it actually is getting from the Ethereum blockchain. So you can see once you get that ethers connection, we can get all kinds of information from the blockchain.  

[about wei](docs.ethers.io/v5/api/utils/display-logic)

![image](https://user-images.githubusercontent.com/53083156/225755641-0fc5282d-41d5-43fb-a159-fafdefb251e1.png)

###  Using providers 

Ethers.js supports different APIs through their provider. Let's look at some of these providers and when and why you might want to use them. 
If you look at the provider's section of the ethers doc, you might have noticed there's a list of some API providers. The beauty of ethers is that no matter which one you use, they basically all use the same API, which means it's pretty easy to switch from one another based on your needs. In fact, you can set up a default one and then have other fallback providers so that you have some redundancy, which is again, the power of decentralization. You want to have that redundancy. 

So these providers are the equivalent of using something like AWS, Azure or Google Cloud for hosting, but it's Ethereum. They give you the reliability and speed of a managed redundant network of Ethereum nodes. It's a great practice for making smooth-running dapps. And many of the dapps you use take advantage of them to enhance user experience. Things like OpenSea, and SuperRare, and (indistinct) they all use them. 

So ethers has a predefined set of API keys that will work and are fine for testing. But if you go into production, you're going to want to make sure you go and get your own.

[Alchemy](https://www.alchemy.com) is a very popular one and you can see there's a number of good projects that use these. They have a lot of tools in addition to ethers.js that can support you in building them; dashboards and things so you can easily change things. And there's new things coming out all the time; push notifications and whatnot.

[Infura](https://infura.io) is another very popular one that's used by a lot of different projects. Highly available. They also have IPFS in Infura, which is a nice add. And some of these actually support some layer 2 networks, like Polygon and Arbitrum, which is nice because those are sort of built around Ethereum to save on gas prices.

[Etherscan](https://etherscan.io/), which is the popular block explorer, they have their own API. 

[Pokt](https://www.pokt.network/). They have their own POKT token that you can use. And they actually support some other chains in addition to Ethereum as well.

[Ankr](https://www.ankr.com/) is another one that's up and coming that you'll see.

Each of them has their own different sort of specialty, depending on the type of dapp you're building, and what your constraints are, and if you're supporting multi-chain, if you're using layer 2, those kind of things. And all these supported out of the box by ethers.js. So you just need to get a key, and plug it in.

There are many other tools that will be available within these environments, depending which one you're using. And you may or may not need different JavaScript libraries and different things to activate those. Now, another great way to access data on the Ethereum blockchain is by using The [Graph](https://thegraph.com/en). If you're familiar with GraphQL, The Graph is basically an indexing protocol that uses GraphQL so that you can call them into your dapps. It has its own token. It's a decentralized project. And you can create queries. And they have their own console in here. You can create your own subgraphs that you can then query when you need to. This is going to speed up your experience. It's going to make it a lot faster to read from the blockchain and get data that you need. In addition, there are ways that you can make crypto off of this by hosting nodes, by becoming a curator, and even by creating your own subgraphs. The Graph, of course, is a great way to get blockchain data in GraphQL format.

Using these third-party providers is a great way to enhance the performance of your dapps. The nature of decentralization is that it's very slow, but these kind of tools can be a great intermediator. So that way you can give your users a better and faster experience, but it's still going out to the blockchain. Ultimately, all of these things sync to the blockchain and they're getting blockchain data. 

###  Calling a smart contract function 

We need to make sure that we've got our front end running and that we've got our Ethereum node running and essentially we're ready to go and we've deployed our contract. 

Go to the root of my dapp, which is where smart contracts are. Type (or .js):
	
	npx hardhat run --network localhost scripts/mint-script.ts

to make sure it deploys to the local host and run scripts/mint-script.js, which is the one that deploys our minting contract.

Compiled. And it's deployed to that address. So, copy the address. 

In the Solidity project and you'll notice there's this Artifacts folder. Now in here, there's my contracts. And there's actually a folder called "SOL." There's this item here called "BinaryvilleRobotsNFT.JSON." (DappNFT.json instead). And one of the things you can see is this [ABI](https://docs.ethers.org/v5/api/utils/abi/formats/). Now, I'm going to need this. I'm actually going to cut this from the beginning of that square brace down to the closing square brace right here. So, I'm going to cut that out, not right now, but later.

Back in my navbar. Now, I have my mint function and this is what I'm going to fill in now. I'm going to need this copied contract address. So, now I'm going to take that contract address and put in here. It's the same. So, I've added my contract address in here. And what I'm doing is I'm creating a new constant that's representing my contract, using the ethers.contract object, and then I'm passing this iface, and the signer. Iface that is what I'm getting from the ABI. So, I'm creating a constant, jsonAbi, which is this ABI. And the ABI is really just a representation of the contract. Now, ideally you want to put it in human readable format where it just basically says what the different functions are. It has the constructor, it has the variables, but it looks like functions that are written. JSON isn't as human readable, it's defining the same thing but it's really meant to be parsed by a parser. So, what I'm going to do is I'm actually going to take it and I'm going to translate it using this interface here. And then, this will change it to essentially human readable format behind the scenes, and we cannot put that, but for now, you don't need to worry about that. Just know that I'm basically passing the ABI there. So, the ABI, that and the signer, will essentially get the contract set up. And then, I'm going to go ahead and create NFT data. And then, I'm going to call the mint NFT function. Now, instead of this, I'm going to pass URL. The IPFS:// will work if you're using a resolver that will resolve that. Now, a lot of browsers, AKA user agents, don't do that. So, I'm going to go ahead and get my address from pinata. And I can just copy that, 'cause this is exactly that. And I can put that in here as the token URI, and that's the metadata, keep in mind, which will refer to the image that we have. 

Now, I can go to my DApp. Oh, something's not working. So, let's go and have a look. Okay. So, we have a problem. Problem, an expected reserve word, "await." Ah, I see what the problem is. Our function should be an async function, 'cause we're using await.  Let's have a look again. Ah, interface and format types. Yes, yes, yes. You need to make sure to import those. So, now it compiled. So, let's reload it. Connect our wallet. We'll go to mint and it should bring up the wallet. It's telling me some information about gas and all that. Yes, I can close that and how much it's going to cost and I'm going to confirm it and it's off and running. Now, we can view JavaScript console. And it up with this, which tells me that it succeeded. Definitely took some gas, mint NFT. By the zero E was free and it happened, tells me information about it. It's been confirmed. So, that's it. We've now minted our NFT successfully.

![image](https://user-images.githubusercontent.com/53083156/225758209-13e1b099-3f09-44be-a079-7f520fe79111.png)

take this and put it in mintNFT function instead of ipfs://test-uri:
![image](https://user-images.githubusercontent.com/53083156/226060079-702a161c-b97c-44bb-b516-08dd4c52d21a.png)


###  Bringing it all together 

Now that we've successfully minted our dApp, let's talk about what's missing and what we might do to finish this all off. So if we had more time, there's a few things we'd probably want to do. One of those things would be when the user logs in, to put their wallet information up here, maybe just abbreviated and the last four or something like this. Excuse my messy writing. (laughs) But you can see the idea, right? And then the user can connect and reconnect, and they can sort of manage their connection to our dApp through that interface. And I think that's a really good way to do it. Now, the ERC-721 spec allows for a lot of other things, and OpenZeppelin has a lot of things you can do in terms of customizing your NFT. So we can use things to pause and restart the minting. We can have it so that token holders can burn their own tokens. We have ways that you can use these to vote. So there's all kinds of things that you might want to implement. So I would say, definitely look at the ER-721 docs and see if there might be something else you'd want to do. Now also, when we minted, we passed the actual NFT data through our metadata, but what you might want to do is something like this. So these are all minted NFTs, and this is a project on the Stacks blockchain. So it's not Ethereum, but the same basic concept holds no matter what chain you're on. And I love this project. This artist, Grace Hye, she's in Paris, and it's just this beautiful sort of work that she's done. And if you own this, you have access then to her actual real art that you can order, which is super cool. So I bought one of these, and I'm waiting for my reveal. So this reveal thing is something that people do a lot of because it's a fun way to do it. Let people mint out. It encourages also getting the full mint because while you're waiting for the reveal, you might be helping promote other people. "Hey, buy this NFT so that we can all see what we've got." So it's a good way to do it. And then usually they have a reveal party. And it's fun to sort of see what's happening. And everyone does it at the same time. And you can be virtual and sharing things in Discord and all that good stuff. So it's a good way to do NFT projects. And the way you do it, there's a couple different ways. And I'm just going to talk through them here. One is you can actually create a folder. So you can have a folder with all of your metadata in it for the pre-mint, right? And then you set up the pre-mint and you upload it. And then you can basically just change that folder handler and everything will then refresh to whatever the new sort of data is. So you're not changing the CID. You're just changing the ID of the folder. So that's one way that people do it. Another way you can do it is you have your tokenURI function that returns the token URI. And based on sort of the date, time, you can return either the metadata per this, right? Which would actually be the sort of pre-reveal. And then once it's post-reveal, you would then return the metadata that has the actual NFT on it. And it would just be, like, a matter of having a different folder and the same sort of JSON file that you're linking to for the metadata, with an ID in it or something like that. So that's a pretty straightforward way to do it, and that's what a lot of projects do. You just have to remember to build that into your NFT before you upload it and before you mint. So that's something else you can do. Another thing to mention is the concept of a whitelist. What typically will be done is you'll collect a list of wallet addresses and you'll have first a private minting that maybe costs less and anyone that's on that list. So there's two basic ways to do this. One way is we can essentially have all of those wallets in the contract. So we can submit the wallets either in a single transaction as an object or individually one at a time. Now those cost gas because we're going to be writing them to the blockchain and the NFT. And then, of course, you need to make sure you write a function that only you can call that would be able to upload that. So it'd have to have the ownable implementation. The other way to do it is to do it off chain. And essentially what you'd do is create a signature, where that signature would effectively be passed along with the mint, and that signature would come from the wallet address. And so you'd have some way of validating that, that it's accurate on the other side when it goes to mint. It's a little more complicated, but it is a way to do it, and it doesn't cost gas 'cause you can do it off chain. So, a popular way to do it. So that's basically the couple things I would do in addition to, of course, doing all these things in batch, which you can do 'cause there's APIs. And like here, you can just upload a folder instead of having to upload one file at a time. So those are the things that I think you would need to really finish this off and make it an actual minting dApp, but it's really close. The core is here, and you're pretty much ready to go. So over the course of this course, you've actually built an NFT-minting site that works. That's pretty amazing! You should be proud of that. So there're a few things you might want to do to round it out, but otherwise, you're ready to get out there and learn more and start building some dApps. In the next and last unit of this course, we're going to talk about where to go and what to do to continue your journey of becoming a Web 3.0 master programmer. 

# Exception handling

Exception:
```
  opensslErrorStack: [ 'error:03000086:digital envelope routines::initialization error' ],
  library: 'digital envelope routines',
  reason: 'unsupported',
  code: 'ERR_OSSL_EVP_UNSUPPORTED'
```

Solution:
```command
set NODE_OPTIONS=--openssl-legacy-provider
```
