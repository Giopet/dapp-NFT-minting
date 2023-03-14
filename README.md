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

![image](https://user-images.githubusercontent.com/53083156/225140844-45ce0ea4-734b-4300-b029-502bfe04e07b.png)

Let's take a look at the details of today's ethereum full stack:
- The wallet is typically **MetaMask**.
- **web3.js** was the original JavaScript client library, and this is supporting interacting with the wallet and talking to the blockchain. However **Ethers.js** has evolved, and it's a newer library and it's a little bit smaller and more well documented, and even has some other benefits.
- Testing of smart contracts is typically done in **Truffle** if you're using web3.js suite, and in **Waffle**, which is new, and that goes along with the Ethers.js.
- When you want to interact directly with the blockchain, it used to be you had to run a node and really look through things quite manually. However, now there are a number of APIs available, including The **Graph**, **Alchemy**, **Morales**, **Infura**, and these have all made it a lot easier, not to mention we don't have to maintain nodes, they can maintain well performing nodes for us.
- The file system has settled to pretty much the interplanetary file system(**IPFS**) as the decentralized source of data. Swarm still exists, but most applications today in NFT projects tend to use IPFS for storage. And the arrival of pinata is a nice user friendly layer that sits on top of IPFS and makes it easy to interact with. 

![image](https://user-images.githubusercontent.com/53083156/225144821-67ab40d0-ceca-42bd-a068-615cfe295482.png)

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

## Architecture of the DApp

![image](https://user-images.githubusercontent.com/53083156/225164875-f0d88a6b-6e94-4407-9d08-9b3bf9d8d5f5.png)

The front end will be React, JavaScript, HTML, and CSS, like pretty much any Web 2.0 site. We use JavaScript libraries to talk to the blockchain, which is Ethers.js.

The web files and assets can be hosted on either IPFS or traditional web hosting environments, AKA, we'll just call it the cloud.
Keep in mind that if you're hosting solely on IPFS, then you'll need to have the site available via the Ethereum Name Service (ENS), and you're going to have less control over performance and latency. But it will be more decentralized. A site hosted in the cloud is subject to the normal issues of centralization, which is it can be hacked, it can be DDoS-attacked, and generally speaking, it's more centralized. So it can be blocked as well.

We'll use a smart contract to generate our NFTs. There are many uses for smart contracts, but the minting and handling our NFT transactions, the actual NFT contract will be the main one that we use for this particular dApp. 

These will then be deployed to Ethereum and they will be deployed out towards the entire Ethereum blockchain. 

We'll store the images and metadata for our NFTs on IPFS. This will provide a nice decentralized storage mechanism that's secure, each will be uniquely identified, and there's assurances to anyone who's buying our NFTs that we can't change them because the CIDs will be contiguous.

We can also read from the blockchain, if we want to, using third party APIs, like Infura, Alchemy, and The Graph.





