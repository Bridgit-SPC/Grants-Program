# Mintbase Grant Proposal

> See the [Grants Program Process](https://github.com/Mintbase/Grants-Program/#pencil-process) on how to submit a proposal.

- **Project Name:** Metaweb NFTBook
- **Team Name:** Bridgit To The Future, LLC
- **Payment Address:** bridgit-dao.sputnik-dao.near
- **[Level](../README.md#level_slider-levels):** 2

## Project Overview :page_facing_up:

This project is to set up a NFT minting and staking site for a book on emerging technology, whereby 50% of the author royalties and 50% of the NFTbook sales revenues (after 15% provided to the publisher) are allocated to the staked NFTs.   

### Overview

Please provide the following:

Decentralizing ownership of an IRL and NFT book

Bridgit DAO is authoring a book called “The Metaweb: The Next Level of the Internet”. The book is about a new layer on top of the web that creates decentralized public space above the web page, which will drastically reduce the problems with false information, abusers, and scammers, as well as enable an unprecedented level of connection and coordination that is necessary to deal with our existential threats.
Our publisher is the renowned [Taylor & Francis](https://taylorandfrancis.com). This will be both a physical book and a NFT book (Taylor & Francis' first NFT book). 

We will start out with a generative Pre-sale NFT series. Purchasers of the Pre-sale NFTs will be airdropped a NFT book upon the release of the IRL book (slated for early 2023). Holders of the Pre-sale NFTs and the NFTbook will have the option to stake. Staked NFTs will earn a royalty allocation based on the relative time staked and the staking power of the staked NFTs. (The Pre-sale NFTs and NFT Books will have different staking powers.) 50% of the author royalties and 50% of the NFTbook sales revenues (after 15% provided to the publisher) are allocated to the staked NFTs.       

We will create Mintbase modules that support the minting and staking of NEAR NFTs. The Pre-sale NFTs can also be listed on our Mintbase store for secondary sale. 

We are interested in creating this project because  we are excited about decentralizing the ownership (as reflected by a royalty allocation) of IRL assets. We think NFTs can accelerate the adoption of the technology explored in the book as well as increase the sales and distribution of the physical book and the NFTbook. We think NFT staking has huge potential especially when connected to real world revenue streams. We are also excited about the possibility of  helping Taylor & Francis do NFTbooks for other books in their catalog.  

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Mockups/designs of any UI components
- Data models / API specifications of the core functionality
- An overview of the technology stack to be used
- Documentation of core components, protocols, architecture, etc. to be deployed
- PoC/MVP or other relevant prior work or research on the topic
- What your project is _not_ or will _not_ provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious

### Ecosystem Fit

This project fits into the ecosystem as website that enables people to mint and stake pre-sale Mintbase NFT and NFT books to earn royalties.   

Our target audience is readers of high technology books, Web3 fans, developers, entreprenuers, and marketers.  

Our project provides a way for people to participate in the Next Level of the Web as a early supporter and funder, and thereby to recieve an allocation of the royalties from the sales of the book and the NFTbook. The funds raised will go to the expenses associated with the production, marketing, and distribution of the book and the NFTbook, enabling the book to be    

- Are there any other projects similar to yours in the Mintbase / NEAR ecosystem?
Yes. 

- If so, how is your project different?
There are two NFTbook prjects on NEAR but they do not use NFTs as a crowdpooling vehicle for NFTbooks 
  https://www.mintbase.io/thing/zUlYU-KEF7i2V1ozFaDsyUCQP9-aVKxfcj9IhcieP-g:writersguild.mintbase1.near This is simply a poetry book
  https://youtu.be/vkDVF3nXivQ This project creates a platform that serializes books so they are released a chapter at a time 
  Ref Finance allws staking of NFTs to earn $REF starting with the Antisocial Ape Club and NEARNauts NFTs: https://medium.com/nearprotocol/stake-your-nfts-receive-ref-rewards-cc847e424fae

## Team :busts_in_silhouette:

### Team members

- Team leader: Daveed Benjamin
- Team member: Reiser Stern

### Contact

- **Contact Name:** Daveed Benjiman
- **Contact Email:** daveed@bridgit.io
- **Website:** https://bridgit.io

### Legal Structure

- **Registered Address:** 30 N. Gould St Ste R, Sheridan, Wyoming 82801
- **Registered Legal Entity:** BRIDGIT TO THE FUTURE LLC

### Team's experience

Reiser did a NFT staking project on NEAR in which he enabled users to stake an NFT to earn tokens. 

### Team Code Repos

We do not have code Github repositories. Bridgit is a contributor to the Presence Browser project but it is a private repository on bitbucket

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/rieserstern
- https://github.com/bridgitbrowser

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/meliaspapa

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

I have spoken briefly with Regina on Telegram about this project and she encouraged me to apply.

The book to be turned into an NFT book is written. Here is the link for you to see the Preface and Introduction, which I think you may find interesting if not thought-provoking: https://bit.ly/metaweb-book-intro.

Here are examples of the art that will be used for the generative Pre-sale NFTs
https://www.dropbox.com/s/mvk7ul8hidjd0ow/metaweb%20png%20examples.gif?dl=0
https://www.dropbox.com/s/jk297lk5oum7qjb/Metaweb%20Presale%20GIF%20example.gif?dl=0

Here is the artwork for the NFT book:
https://www.dropbox.com/s/hvf8g5jx7ge2wdu/Metaweb%20book.gif?dl=0

## Development Roadmap :nut_and_bolt:


### Overview

- **Total Estimated Duration:** 2 months
- **Full-Time Equivalent (FTE):**  1.5 FTE
- **Total Costs:** 35,000 USD

### Milestone 1 — Implement Mintbase Modules for Generative NFT Mint with scheduled Airdrop of NFTbook utility

- **Estimated duration:** 1 month
- **FTE:**  1.5
- **Costs:** 17,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Mintbase nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 1. | Mintbase module: Generative Mint | We will create a Mintbase / NEAR module that will randomly select a unique jpg or gif and mint a pre-sale NFT to a specific user wallet upon transfer of mint and gas fees  |  
| 2. | Mintbase module: Airdrop | We will create a Mintbase / NEAR module that will airdrop a NFTbook to holders of the pre-sale NFT upon demand |  
| 3. | Develop marketing plan and materials | We will develop a marketing plan and content for the pre-sale NFT launch |  

### Milestone 2 — Implement Mintbase Modules for Staking NFT and Paying Royalties to NFT Holders

- **Estimated Duration:** 1 month
- **FTE:**  1.5
- **Costs:** 17,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | GPLv3 / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Mintbase nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Mintbase module: Stake | We will create a Mintbase / NEAR module that will enable holders to stake their pre-sale NFT and NFTbook |  
| 2. | Mintbase module: Pay Royalties | We will create a Mintbase / NEAR module that will pay royalties on demand by admin to stakers based on the relative time staked and the staking power of their staked pre-sale NFT and/or NFTbook |  
| 3. | NEAR chain integration | Modules Generative Mint, Airdrop, Stake, Pay Royalties, Public Webpage, and Admin Webpage of our custom chain will interact in such a way that the user mint a Pre-release NFT, the admin can airdrop the official NFTbook when the book is released, the pre-sale NFT holder can stake their pre-sale NFTs and/or NFTbooks, and the admin can trigger royalty payments as appropriate. |  
| 4. | Implement launch plan | We will launch the pre-sale NFT using various channels including social media, press releases, and a launch event. |  

...
## Future Plans

In the short term, we wil work with the publisher and independently to become an early supporter and owner of the book by purchasing a pre-sale NFT, a NFT book, or a physical book. This includes regular social media posts, press releases, blog posts, and a worldwide Metaweb NFT and book tour. Supporters can also join the Bridgit DAO and get compensated for activites that advance the book.   

In the medium to long term (once we have proven the model), we will approach our publisher and potentially other publishers about enabling their authors to decentralize ownership of their books.  We will also use abstract the code to be used to support minting and staking NFTs for any IRL/virtual project with a revenue stream.      



## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Mintbase home page

We have already created the assets for the generative pre-sale NFT launch and the NFT book.  
