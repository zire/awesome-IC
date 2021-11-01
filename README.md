# Awesome Internet Computer


A collection of projects and Dapps built on Internet Computer (IC) ecosystem. Visit [https://zire.github.io/awesome-IC/](https://zire.github.io/awesome-IC/) to view it on desktop or mobile.

![dfn logl](https://1082-xyz.s3.us-west-1.amazonaws.com/dfn_logo.png)

Total # of IC dApps indexed: `111` as last updated on `Nov 1, 2021`. This is not a complete list yet and more will be added in the coming days.

- Essential (`3`)
- Wallet (`4`)
- Tools (`16`)
- Motoko (`3`)
- DeFi (`11`)
- NFT (`32`)
- Social (`9`)
- Games (`10`)
- Metaverse (`3`)
- Productivity (`8`)
- Communities (`4`)
- Enterprise (`8`)

This page tries to capture key info for each project, including its tag line, IC URL, Twitter, Discord, Telegram, Github repo and the team behind. For those projects with Twitter handles, they can also be found at:

> [IC Projects - All@Twitter](https://twitter.com/i/lists/1443165233510436868)

This list includes all the projects from [DFINITY Showcase](https://dfinity.org/showcase/) but is a lot more than that. It tries to index all the known IC dApps. Some of those projects have received [developer grants from the DFINITY Foundation](https://dfinity.org/grants/). Some of them may not have been deployed on IC yet - though the expectation is that they are working toward that. It does not include IC communities, media or development teams per se (though they'll be included under the "project" section). All info is obtained from public channels. 

The projects indexed on this list cover a wide spectrum on quality, maturity and tech deployment. Some of them have already received venture funding from established crypto funds; some of them are taking full advantage of Internet Computer (IC)'s unique technical strengths; some of them are using IC as a backend infrastructure in liew of AWS/GCP, and some of them are porting an existing Polkadot/Filecoin application to IC. The inclusion of a project (or lack of) does not speak to the quality of it. That judgment is left to the community and all IC advocates. This is just a directory that helps everyone do scavenger hunt on IC.

If you find an IC dApp is still missing from this page, please [send a PR to its Github repo](https://github.com/zire/awesome-IC) so that I can merge, or [DM me on Twitter](https://twitter.com/herbertyang), or [send me an email](mailto: herbert.yang@dfinity.org?subject=More dApp on Awesome IC). Suggestions on how to make this site more useful to the community are very welcome. Many thanks. 

**DISCLAIMER**: 
>This **`Awesome Internet Computer`** is a community project by IC volunteer(s). It's merely an index/directory, and does not represent official endorsement (or lack of) from the DFINITY Foundation in any fashion.  Nothing from this site shall be treated as financial advice. Please do your own research if you need to use any services listed below.

## Essential (3)

**ICA Network Status**

- What: Real-time dashboard of key metrics on the Internet Computer
- Where: [https://dashboard.internetcomputer.org/](https://dashboard.internetcomputer.org/)
- Who: [Internet Computer Association](https://internetcomputer.org/)

**Internet Identity**

- What: Internet Identity guarantees that your data isn’t visible, tracked, or mined. The blockchain authentication system enables users to sign in to dapps on the Internet Computer and sites across the web anonymously and securely.
- Where: [https://identity.ic0.app/](https://identity.ic0.app/)
- Who: [DFINITY Foundation](https://dfinity.org)

**NNS Dapp**

- What: The NNS front-end dapp allows anyone to interact with the Internet Computer's Network Nervous System with a user-friendly UI. Served completely end-to-end through blockchain, this dapp allows you to manage ICP, stake neurons, participate in voting, and earn rewards.
- Where: [https://nns.ic0.app/](https://nns.ic0.app/)
- Who: [DFINITY Foundation](https://dfinity.org)

## Wallet (4)

**ICWallet**

- What: Your gateway to Dfinity ecosystem
- Where: [https://icwallet.org/](https://icwallet.org/)
- Twitter: [https://twitter.com/icwallet](https://twitter.com/icwallet)
- Who: [https://icwallet.gitbook.io/icwallet/team](https://icwallet.gitbook.io/icwallet/team)
- Discord: [https://discord.com/invite/DqCeHU8rem](https://discord.com/invite/DqCeHU8rem)

**Plug**

- What: A browser extension that allows you to access your ICP, Cycles and other tokens
- Where: [https://plugwallet.ooo/](https://plugwallet.ooo/)
- Who: [fleek](https://fleek.co/)
- Twitter: [https://twitter.com/plug_wallet](https://twitter.com/plug_wallet)
- Discord: [https://discord.gg/yVEcEzmrgm](https://discord.gg/yVEcEzmrgm)

**Stoic Wallet**

- What: It allows anyone to create a digital wallet, authenticating users through a variety of methods.
- Where: [https://www.stoicwallet.com/](https://www.stoicwallet.com/)
- Who: [Toniq Labs](https://igpeu-waaaa-aaaad-qaava-cai.raw.ic0.app/)
- Github: [https://github.com/Toniq-Labs/stoic-wallet](https://github.com/Toniq-Labs/stoic-wallet)

**Earth Wallet**

- What: The open-source wallet allows users to participate in DeFi, Governance, and Treasury (DAO) protocols with negligible fees and faster transaction settlement than legacy wallets.
- Where: [https://www.earthwallet.io/](https://www.earthwallet.io/)
- Twitter: [https://twitter.com/earthwallet](https://twitter.com/earthwallet)
- Discord: [https://discord.gg/B8G75XZ92K](https://discord.gg/B8G75XZ92K)
- Telegram: [https://t.me/earthwallet](https://t.me/earthwallet)
- Github: [https://github.com/earth-association](https://github.com/earth-association)

## Tools (16)

**AstroX**

- What: AstroX is a blockchain development group focused on building tools for the Web3.0 ecosystem. AstroX has developed a Dart agent and other tools to help support mobile application development on the Internet Computer blockchain.
- Where: [https://astrox.medium.com/](https://astrox.medium.com/)
- Who: FireStack Labs
- Twitter: [https://twitter.com/Astrox_Network](https://twitter.com/Astrox_Network)
- Discord: [https://discord.com/invite/Ky78nq4Nag](https://discord.com/invite/Ky78nq4Nag)
- Github: [https://github.com/AstroxNetwork](https://github.com/AstroxNetwork)

**Axon**

- What: A community-built neuron management solution for the Internet Computer. Multiple users can own an Axon that manages multiple neurons within the Network Nervous System, as well as delegate votes to other neurons to vote on proposals. Axon is a multi-user, multi-neuron management canister smart contract.
- Where: [https://axon.ooo/](https://axon.ooo/)
- Twitter: [https://twitter.com/axon_ooo](https://twitter.com/axon_ooo)
- Github: [https://github.com/FloorLamp/axon](https://github.com/FloorLamp/axon)

**B9 Labs**

- What: Better developer onboarding and documentation on IC
- Where: [https://b9lab.com/](https://b9lab.com/)
- Twitter: [https://twitter.com/b9lab](https://twitter.com/b9lab)
- DFINITY Grant: received in August 2021

**Canlista**

- What: The Internet Computer community canister registry. Find, publish and extend applications and services built on the Internet Computer. Log in with Internet Identity.
- Where: [https://k7gat-daaaa-aaaae-qaahq-cai.ic0.app/](https://k7gat-daaaa-aaaae-qaahq-cai.ic0.app/)
- Twitter: [https://twitter.com/canlista_io](https://twitter.com/canlista_io)

**Canistore**

- What: Next-gen #SocialStore powered by @DFINITY, empowered by community 
- Where: [https://canistore.io/](https://canistore.io/)
- Twitter: [https://twitter.com/canistore](https://twitter.com/canistore)
- Telegram: [https://t.me/canistore](https://t.me/canistore)
- Medium: [https://medium.com/@canistore](https://medium.com/@canistore)

**ChainIDE**

- What: a cloud-based multi-chain IDE
- Where: [https://chainide.com/](https://chainide.com/)
- Who: [White Matrix](https://whitematrix.io/) and [https://twitter.com/MatrixDapp](https://twitter.com/MatrixDapp)
- Twitter: [https://twitter.com/ChainIde](https://twitter.com/ChainIde)
- Medium: [https://t.co/ODqRqGNUoG?amp=1](https://t.co/ODqRqGNUoG?amp=1)
- Github: [https://github.com/WhiteMatrixTech](https://github.com/WhiteMatrixTech)
- DFINITY Grant: received in May 2021

**DAB**

- What: DAB provides seamless access to #InternetComputer data that many apps/UI's need to surface. Such as lists of NFT's, tokens, canister/Dapp metadata, and more.
- Where: [https://dab.ooo/](https://dab.ooo/)
- Twitter: [https://twitter.com/dab_ooo](https://twitter.com/dab_ooo)
- Doc: [https://docs.dab.ooo/](https://docs.dab.ooo/)

**DFINITY Explorer**

- What: DFINITY Explorer, a project started in 2018, is an open-source, community-built dashboard and explorer for the Internet Computer, providing live information and statistics about the network, governance, and the ICP utility token, including account and transaction information.
- Where: [https://www.dfinityexplorer.org/#/](https://www.dfinityexplorer.org/#/)
- Who: [Dylan Miller](https://github.com/dylancm4)
- Twitter: [https://twitter.com/dfinityexplorer](https://twitter.com/dfinityexplorer)
- Github: [https://github.com/dfinityexplorer/dfinityexplorer-dashboard](https://github.com/dfinityexplorer/dfinityexplorer-dashboard)

**Dstar**

- What: a marketplace that facilitates listing, buying and selling of your Internet Identity ("II") accounts 
- Where:
	- [https://support.dstar.app/#/](https://support.dstar.app/#/)
	- [https://yunqk-aqaaa-aaaai-qawva-cai.ic0.app/](https://yunqk-aqaaa-aaaai-qawva-cai.ic0.app/)

**Fleek**

- What: Fleek brings decentralized web-hosting to the Internet Computer. With thousands of webpages deployed, Fleek enables anyone to deploy their content on Web3.0
- Where: [https://fleek.ooo/](https://fleek.ooo/)
- Twitter: [https://twitter.com/fleek_ois](https://twitter.com/fleek_ois)
- Discord: [https://discord.gg/yVEcEzmrgm](https://discord.gg/yVEcEzmrgm)
- Github: [https://github.com/FleekHQ](https://github.com/FleekHQ)

**ICME**

- What: ICME is a no-code tool that makes it easy for anyone to build and deploy beautiful websites on the Internet Computer. Launch your blog or business's website on the Internet Computer today.
- Where: [https://sygsn-caaaa-aaaaf-qaahq-cai.raw.ic0.app/](https://sygsn-caaaa-aaaaf-qaahq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/icme_app](https://twitter.com/icme_app)

**ICP Neuron Calculator**

- What: The Network Nervous System Calculator is a calculator that allows anyone to edit variables and estimate voting rewards based on number of proposals voted on, length of stake, accumulated maturity, and more.
- Where: [https://networknervoussystem.com/](https://networknervoussystem.com/)
- Twitter: [https://twitter.com/NNSystem](https://twitter.com/NNSystem)
- Newsletter: [https://allthingsinternetcomputer.substack.com/](https://allthingsinternetcomputer.substack.com/)

**IC Rocks**

- What: IC.Rocks is a complete "block explorer" for the Internet Computer – built by the community. Tracking everything from transactions, to network upgrades, to cycles, IC.Rocks enables anyone to explore the inner-workings of the Internet Computer.
- Where: [https://ic.rocks/](https://ic.rocks/)
- Who: [Norton Wang](https://twitter.com/floatfloatboat)
- Twitter: [https://twitter.com/ic_rocks](https://twitter.com/ic_rocks)

**Pocket 4D**

- What: A framework container runs Mini-Apps or Mini-Programs, using enhanced Canister of cross-platform.
- Who: [Michael So](https://twitter.com/ghostcorn) and the team
- Github: [https://github.com/Pocket4D/Pocket4D-Wiki](https://github.com/Pocket4D/Pocket4D-Wiki)

**Sudograph**

- What: Sudograph is a GraphQL database for the Internet Computer. Its goal is to become the simplest way to develop applications for the IC by providing flexibility and out-of-the-box data management.
- Where: [https://i67uk-hiaaa-aaaae-qaaka-cai.raw.ic0.app/](https://i67uk-hiaaa-aaaae-qaaka-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/lastmjs](https://twitter.com/lastmjs)
- Github: [https://github.com/sudograph/sudograph](https://github.com/sudograph/sudograph)

**The Wall**

- What: The Wall is a dapp built on the Internet Computer blockchain, which blends Ethereum's MetaMask authentication with the Internet Computer's native Internet Identity blockchain authentication system. This first example of ETH x ICP allows users to leave any message on the wall for all eternity.
- Where: [https://rivyl-6aaaa-aaaaf-qaapq-cai.raw.ic0.app/](https://rivyl-6aaaa-aaaaf-qaapq-cai.raw.ic0.app/)
- Github: [https://github.com/kristoferlund/ic-wall](https://github.com/kristoferlund/ic-wall)
- Who: [Kristofer Lund](https://twitter.com/kristoferlund)

## Motoko (3)

**Block.**

- What: A virtual editor for Motoko

**Motoko Playground**

- What: The Motoko Playground is an IDE for developers to learn Motoko – the native language for the Internet Computer blockchain. Deploy canister smart contracts for free, directly within a browser, without needing to download an SDK or set up a wallet.
- Where: [https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/](https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/)
- Who: [Chen Yan](https://forum.dfinity.org/u/chenyan/)

**Matoko School**

- What: Motoko School is the first public school for the Metaverse, only on the Internet Computer
- Where: [Mototko School on Youtube](https://www.youtube.com/channel/UCS2Y9oRMpBfVqAnChFoXepg)
- Twitter: [https://twitter.com/MotokoSchool](https://twitter.com/MotokoSchool)

## DeFi (11)

**Bauction**

- What: Bauction will empower the online auction and tender for retail as well as enterprises customer is decentralized and transparent manner. By leveraging technology stack of ICP, we want it to be self governed self driven auction platform.
- Where: [https://bauction.org/](https://bauction.org/)
- Twitter: [https://twitter.com/bauctionorg](https://twitter.com/bauctionorg)
- DFINITY Grant: received in July 2021

**CetoSwap**

- What: CetoSwap ∞ is a fungible and non-fungible asset management platform base on #Dfinity
- Where: [https://ijnlb-jiaaa-aaaah-qaesa-cai.ic0.app/](https://ijnlb-jiaaa-aaaah-qaesa-cai.ic0.app/)
- Twitter: [https://twitter.com/CetoSwap](https://twitter.com/CetoSwap)
- Medium: [https://cetoswap.medium.com/](https://cetoswap.medium.com/)

**Dank**

- What: Dank is the first Decentralized Bank built on the Internet Computer, developed by Fleek. Through a collection of Open Internet Services for users and developers, Dank makes cycles management seamless.
- Where: [https://dank.ooo/](https://dank.ooo/)
- Twitter: [https://twitter.com/dank_ois](https://twitter.com/dank_ois)
- Discord: [https://discord.gg/yVEcEzmrgm](https://discord.gg/yVEcEzmrgm)

**Dfinance**

- What: DFinance is building open financial infrastructure on the Internet Computer. With DeFi products, swaps, unified token standards, token issuance, and token management DFinance is one of the first open and decentralized financial solutions on the Internet Computer.
- Where: [https://dfinance.ai/](https://dfinance.ai/)
- Twitter: [https://twitter.com/DFinance_AI](https://twitter.com/DFinance_AI)
- Discord: [https://discord.gg/EkmnRd99h6](https://discord.gg/EkmnRd99h6)
- Github: [https://github.com/dfinance-tech](https://github.com/dfinance-tech)

**EnsoFinance**

- What: Discover and create open DeFi metastrategies
- Where: [https://www.enso.finance/](https://www.enso.finance/)
- Twitter: [https://twitter.com/EnsoFinance](https://twitter.com/EnsoFinance)
- Discord: [https://discord.gg/y48Yp6Y4QX](https://discord.gg/y48Yp6Y4QX)

**iBridge**

- What: #DeFi Protocol for #Crosschain Assets Based on #Dfinity
- Where: [https://www.ibridge.pro/](https://www.ibridge.pro/)
- Twitter: [https://twitter.com/iBridge_Labs](https://twitter.com/iBridge_Labs)
- Github: [https://github.com/iBridge-up](https://github.com/iBridge-up)
- Medium: [https://medium.com/@ibridge_labs](https://medium.com/@ibridge_labs)

**ICPSwap**

- What: ICPSwap is decentralized exchange (DEX) built completely end-to-end on-chain. By building the ability for anyone to swap tokens through ICPSwap leveraging the Internet Computer blockchain as the high-speed, scalable, low-cost infrastructure makes ICPSwap a first-to-market in the growing Internet Computer DeFi ecosystem.
- Where:
	- [https://3pbcj-viaaa-aaaah-qaajq-cai.raw.ic0.app/](https://3pbcj-viaaa-aaaah-qaajq-cai.raw.ic0.app/)
	- [https://twitter.com/ICPSwap](https://twitter.com/ICPSwap)
- Twitter: [https://twitter.com/ICPSwap](https://twitter.com/ICPSwap)
- Telegram: [https://t.me/ICPSwap_Official](https://t.me/ICPSwap_Official)
- Medium: [https://icpswap.medium.com/](https://icpswap.medium.com/)
- DSCVR: [https://h5aet-waaaa-aaaab-qaamq-cai.raw.ic0.app/p/icpswap](https://h5aet-waaaa-aaaab-qaamq-cai.raw.ic0.app/p/icpswap)
- Github:[https://iloveics.gitbook.io/icpswap/](https://iloveics.gitbook.io/icpswap/)

**InfinitySwap**

- What: A platform to create, stake and swap Dfinity Tokens
- Where: [https://infinityswap.one/](https://infinityswap.one/)
- Twitter: [https://twitter.com/infinity_swap](https://twitter.com/infinity_swap)
- Telegram: [https://t.me/infinityswapofficial](https://t.me/infinityswapofficial)

**Liquid ICP**

- What: Liquid ICP is world's first s-Bridge where bridged and staked assets remain liquid. Fractional reserve is governed by Liquid ICP community and ensures immediate withdrawal of ICP coins at any given time.
- Where: [https://www.icp-20.com/](https://www.icp-20.com/)
- Twitter: [https://twitter.com/LiquidICP](https://twitter.com/LiquidICP)
- Discord: [https://discord.com/invite/3F8CYyPpHq](https://discord.com/invite/3F8CYyPpHq)
- Github: [https://docs.icp-20.com/](https://docs.icp-20.com/)

**Sailfish**

- What: The gateway to open financial services on the Internet Computer
- Where: [https://sailfish.app/](https://sailfish.app/)
- Twitter: [https://twitter.com/Sailfishapp](https://twitter.com/Sailfishapp)
- Discord: [https://discord.com/invite/7Wbqucc](https://discord.com/invite/7Wbqucc)

**Uniswap Front End on the IC**

- What: Uniswap front end hosted on the Internet Computer through Fleek. Showing how traditional DeFi solutions can now be hosted completely on-chain by using the Internet Computer blockchain. Another use case of completely decentralizing a service which currently has a centralized front end.
- Where: [https://lqku6-wqaaa-aaaad-qalmq-cai.ic.fleek.co/#/swap](https://lqku6-wqaaa-aaaad-qalmq-cai.ic.fleek.co/#/swap)
- Who: [fleek](https://fleek.co/)

## NFT (31)

**Crowd Created Canvas (CCC)***

- What: CCC is the first-ever collectible, collaborative pixel artwork created by the #Dfinity community, sharing bonus pool and getting NFT.
- Where: [https://sdnoa-fiaaa-aaaah-aaubq-cai.ic0.app/](https://sdnoa-fiaaa-aaaah-aaubq-cai.ic0.app/)
- Twitter: [https://twitter.com/CCCProtocol](https://twitter.com/CCCProtocol)

**Cronic NFTs**

- What: Cronics play-to-earn ecosystem on the $ICP blockchain. Trade Cronic Critters and accessories on 
@EntrepotApp
- Where: [https://cronic.toniqlabs.com/](https://cronic.toniqlabs.com/)
- Who: [Toniq Labs](https://igpeu-waaaa-aaaad-qaava-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/CronicsP2E](https://twitter.com/CronicsP2E)
- Telegram: [https://t.me/cronic_talk](https://t.me/cronic_talk)

**IC Ape Ventures**

- What: 10,000 Unique Apes are getting ready to take their first steps in to the #ICP ecosystem
- Where: [https://icapeventures.com/](https://icapeventures.com/)
- Twitter: [https://twitter.com/ICApeVentures](https://twitter.com/ICApeVentures)
- Discord: [https://discord.com/invite/icapeventures](https://discord.com/invite/icapeventures)

**IC Photographers**

- What: At IC photographers, the aim is to bring both creator and collector together. We endeavour to show talented artists to the collectors of photography NFT’s.
- Where: [https://www.icphotographers.com/](https://www.icphotographers.com/)
- Who: [Oli](https://twitter.com/olisav)

**Dfinity Bulls NFT**

- What: 8,888 Awesome Badass Bulls will ever be minted! Exclusively on ICP!
- Twitter: [https://twitter.com/DBulls_NFT](https://twitter.com/DBulls_NFT)
- Discord: [https://discord.com/invite/GBSNhYeGxh](https://discord.com/invite/GBSNhYeGxh)

**DfinityNFT**

- What: The Cryptogarden of The Internet Computer. NFT cross-chain aggregator of The Internet Computer.
- Where: [http://dfinitynft.com/](http://dfinitynft.com/)
- Twitter: [https://twitter.com/DfinityNFT](https://twitter.com/DfinityNFT)
- DFINITY Grant: received in July 2021

**Exponent**

- What: The Exponent Platform is a complete Layer1 DeFi solution running on DFINITY's Internet Computer. Our platform is made from a number of our token standard, SDK and protocols.
- Who: [Toniq Labs](https://igpeu-waaaa-aaaad-qaava-cai.raw.ic0.app/)
- Discord: [https://t.co/9iDZBX35mg?amp=1](https://t.co/9iDZBX35mg?amp=1)
- Github: [https://github.com/Toniq-Labs/exponent](https://github.com/Toniq-Labs/exponent)

**Entrepot NFT Marketplace**

- What: Entrepot is a decentralized NFT marketplace developed by ToniqLabs, the creators behind Rise of the Magni, Stoic Wallet, Cronic NFTs, and Exponent. Entrepot (through Exponent) provides users with tools and on-chain services to design, deploy, and manage NFTs and traditional tokens.
- Where: [https://entrepot.app/](https://entrepot.app/)
- Who: [Toniq Labs](https://igpeu-waaaa-aaaad-qaava-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/EntrepotApp](https://twitter.com/EntrepotApp)
- Discord: [https://discord.gg/toniqlabs](https://discord.gg/toniqlabs)
- Github: [https://github.com/Toniq-Labs/exponent](https://github.com/Toniq-Labs/exponent)

**Fantosaurs**

- What: Raptors from Isla NOOblar, currently on Eth, but hosted on IC
- Where: 
	- [https://fantosaur.io/](https://fantosaur.io/)
	- [https://j5h4x-gyaaa-aaaad-qayjq-cai.raw.ic0.app/](https://j5h4x-gyaaa-aaaad-qayjq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/fantosaurs](https://twitter.com/fantosaurs)
- Discord: [https://discord.com/invite/e7bec4rm](https://discord.com/invite/e7bec4rm)

**Fungible Token Standard by Deland**

- What: Fungible token standard by Deland
- Where: [https://github.com/Deland-Labs/dfinity-fungible-token-standard](https://github.com/Deland-Labs/dfinity-fungible-token-standard)
- Who: [Deland Labs](https://deland.one/)
- Medium: [https://medium.com/@DelandLabs](https://medium.com/@DelandLabs)
- Discord: [https://discord.gg/CdzzUaFUXq](https://discord.gg/CdzzUaFUXq)
- DFINITY Grant: received in August, 2021

**Haunted Hamsters**

- What: NFT set of 6,666 haunted hamsters, spooking on DFINITY ICP
- Where: [http://www.hauntedhamsters.io/](http://www.hauntedhamsters.io/)
- Twitter: [https://twitter.com/HauntedHamsters](https://twitter.com/HauntedHamsters)
- Discord: [https://discord.com/invite/DtSF7SGK](https://discord.com/invite/DtSF7SGK)

**IC3D**

- What: Cool 3D NFTs on the Internet Computer - IC 3D NFT
- Twitter: [https://twitter.com/IC3DNFT](https://twitter.com/IC3DNFT)
- Discord: [https://discord.com/invite/ic3dnft](https://discord.com/invite/ic3dnft)

**IC Canvas**

- What: a collaborative NFT
- Where: [https://rdbii-uiaaa-aaaab-qadva-cai.raw.ic0.app/](https://rdbii-uiaaa-aaaab-qadva-cai.raw.ic0.app/)
- Who: [Kyle Peacock](https://twitter.com/kylpeacock)

**ICelebrity**

- What: 100 Uniquely Minted handmade artistic representation of the people we know and love!
- Twitter: [https://twitter.com/ICelebrityNFT](https://twitter.com/ICelebrityNFT)
- Discord: [discord.gg/AZFq4QMYBx](discord.gg/AZFq4QMYBx)

**IC Gallery**

- What: Home of the Metaverse. 9999 unique 3D Moonwalker NFTs
- Where: [https://gan2q-ciaaa-aaaai-aanoq-cai.raw.ic0.app/](https://gan2q-ciaaa-aaaai-aanoq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/ic_gallery](https://twitter.com/ic_gallery)
- Discord: [https://discord.com/invite/6VWZNzskPA](https://discord.com/invite/6VWZNzskPA)

**ICP Art**

- What: Exclusive Hand-Crafted Art Collections
- Where: [https://linktr.ee/ICPArt](https://linktr.ee/ICPArt)
- Twitter: [https://twitter.com/ICP_Art](https://twitter.com/ICP_Art)

**ICP Squad**

- What: First Engage To Earn #NFTs Game. Powered by @dfinity
- Where: [https://upf6d-saaaa-aaaah-aauwa-cai.ic0.app/#/](https://upf6d-saaaa-aaaah-aauwa-cai.ic0.app/#/)
- Twitter: [https://twitter.com/ICPSquadNFT](https://twitter.com/ICPSquadNFT)
- Discord: [https://discord.com/invite/icpsquad](https://discord.com/invite/icpsquad)

**ICPunks**

- What: 10,000 randomly generated, unique collectible clowns with proof of ownership stored on the Internet Computer blockchain. Created as a reference to a meme comparing the Internet Computer token (ICP) with the Insane Clown Posse - an American hip hop duo founded in 1989.
- Where: [https://icpunks.com/](https://icpunks.com/)
- Twitter: [https://twitter.com/ICPunks](https://twitter.com/ICPunks)
- Who: [stopak](https://github.com/stopak) and [Przemyslaw Chojecki](https://github.com/przchojecki)
- Github: [https://github.com/stopak/ICPunks/tree/dev](https://github.com/stopak/ICPunks/tree/dev)
- Discord: [https://discord.gg/m8QWD7m62h](https://discord.gg/m8QWD7m62h)

**ICPuppies**

- What: ICPuppies is an NFT project hosted completely on the Internet Computer. In October, 10,000 randomly generated NFTs will be available for members of the Internet Computer community to claim through the Entrepot.app marketplace. A portion of the proceeds will be donated to organizations that support puppies.
- Where: [https://icpuppies.io/](https://icpuppies.io/)
- Twitter: [https://twitter.com/ICPuppies](https://twitter.com/ICPuppies)
- Discord: [http://discord.gg/A3rmDSjBaJ](http://discord.gg/A3rmDSjBaJ)

**ICSnakes**

- What: A collection of 10,000 randomly generated NFTs on #ICP blockchain hunting for food.
- Where: [https://xn--4n8h7h.ws/](https://xn--4n8h7h.ws/)
- Twitter: [https://twitter.com/ICSnakes](https://twitter.com/ICSnakes)
- Discord: [https://discord.com/invite/H9YUpwVrkQ](https://discord.com/invite/H9YUpwVrkQ)

**ICTuts**

- What: 1st pharaohs NFTs in the world ExCLUSIVE @ #ICP  10,000 randomly generated TuTs ( king TuT ).
- Where: [https://ictuts.com/](https://ictuts.com/)
- Twitter: [https://twitter.com/ICTuTs](https://twitter.com/ICTuTs)
- Discord: [https://discord.com/invite/sMByysB3Tf](https://discord.com/invite/sMByysB3Tf)

**Inferval Vampire Colony**

- What: 666 randomly generated Vampires on the Internet Computer
- Where: [https://www.infernalvampires.com/](https://www.infernalvampires.com/)
- Twitter: [https://twitter.com/IVCNFT](https://twitter.com/IVCNFT)
- Discord: [https://discord.com/invite/mA5cXdAtwe](https://discord.com/invite/mA5cXdAtwe)

**Infinite Charity Project**

- What: A nonprofit corporation and charitable org providing non-commercial fundraising for 501(c)3 charities
- Where: [https://chimps.icproject.org/](https://chimps.icproject.org/)
- Twitter: [https://twitter.com/icproject_nft](https://twitter.com/icproject_nft)

**Internet Astronauts**

- What: Internet Astronauts are a set of 10,000 limited edition, uniquely minted astronaut-themed NFTs. These end-to-end on-chain NFTs will be up for grabs to the community through the Entrepot.app marketplace. They are only possible through the Internet Computer blockchain.
- Where: [https://interastrosc.com/](https://interastrosc.com/)
- Twitter: [https://twitter.com/interastrosc](https://twitter.com/interastrosc)

**Meme Cake**

- What: The Cake Club is a collection of 7777 Dick NFTs unique digital collectible living on the Internet computer, made by Meme Cake, which claims to be the world's first decentralized comedy platform. Think of it as a 9GAG but decentralized. 
- Where: [https://memecake.io/](https://memecake.io/)
- Twitter: [https://twitter.com/realmemecake](https://twitter.com/realmemecake)
- Discord: [https://discord.com/invite/vr2ATGMdug](https://discord.com/invite/vr2ATGMdug)

**Newsie**

- What: Comic Book and NFT Collection On The Internet Computer
- Where: [https://gh2ig-jqaaa-aaaai-aaslq-cai.raw.ic0.app/](https://gh2ig-jqaaa-aaaai-aaslq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/NewsieCartoon](https://twitter.com/NewsieCartoon)

**NFT Studio**

- What: NFT Studio allows users to Mint, Buy, Sell and Stake 3DWASM NFTs on the Internet Computer
- Where: [https://7xw5z-uqaaa-aaaad-qaqcq-cai.raw.ic0.app/](https://7xw5z-uqaaa-aaaad-qaqcq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/NFTStudioPoland](https://twitter.com/NFTStudioPoland)
- Discord: [https://discord.com/invite/65P4NzzSQx](https://discord.com/invite/65P4NzzSQx)

**NFT Village**

- What: Look up the attributes, NRI %, rarity, and other information about Internet Computer NFTs. Simply input the URL of your ICPunks and Cronics NFTs or any other NFT minted on the Internet Computer blockchain and learn all of the details that make the NFT unique.
- Where:
	- [http://nftvillage.ai/](http://nftvillage.ai/)
	- [https://nntkg-vqaaa-aaaad-qamfa-cai.ic.fleek.co/](https://nntkg-vqaaa-aaaad-qamfa-cai.ic.fleek.co/)
- Twitter: [https://twitter.com/NFT_Village](https://twitter.com/NFT_Village)

**Pokded Studio**

- What: CHARACTERS! UN-game_land - animation - coming soon
- Twitter: [https://twitter.com/pokedstudiouk](https://twitter.com/pokedstudiouk)
- Discord: [https://discord.com/invite/PokedStudioNFT](https://discord.com/invite/PokedStudioNFT)

**PORTAL**

- What: A Streamers Marketplace Powered by the #InternetComputer
- Where: [https://ja7sy-daaaa-aaaai-qaguq-cai.raw.ic0.app/](https://ja7sy-daaaa-aaaai-qaguq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/PortalDapp](https://twitter.com/PortalDapp)
- Discord: [https://discord.com/invite/FSSauMNrbS](https://discord.com/invite/FSSauMNrbS)

**The Sword NFT**

- What: #ICP exclusive. Follow for updates and airdrop information. Series 1: Little Ninjas. Only 10K Unique Ninjas will be Minted, ever.
- Where: [https://theswordnft.com/](https://theswordnft.com/)
- Twitter: [https://twitter.com/TheSwordNft](https://twitter.com/TheSwordNft)
- Discord: [https://discord.com/invite/Xgc5zTrdSb](https://discord.com/invite/Xgc5zTrdSb)

**Yolo Octopus**

- What: a collection of 8888 intelligently generated NFTs on the Internet Computer blockchain
- Where: [http://www.enteryoloclub.com/](http://www.enteryoloclub.com/)
- Twitter: [https://twitter.com/EnterYoloClub](https://twitter.com/EnterYoloClub)

## Social (9)

**crowdEasts**

- What: Yelp on IC, owned by users
- Where: [https://www.crowdeats.io/](https://www.crowdeats.io/)
- Twitter: [https://twitter.com/crowdeats_io](https://twitter.com/crowdeats_io)
- Discord: [https://discord.gg/Cmm7N9pqsK](https://discord.gg/Cmm7N9pqsK)

**DSCVR**

- What: DSCVR is a decentralized version of Reddit, where users are the owners. Decentralized end-to-end, built on the Internet Computer, and accessible from any browser. 
- Where: [https://h5aet-waaaa-aaaab-qaamq-cai.raw.ic0.app/](https://h5aet-waaaa-aaaab-qaamq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/DscvrO](https://twitter.com/DscvrO)

**Distrikt**

- What: Distrikt is a completely decentralized, community-owned professional network. Users of the platform will vote on upgrades, and no user data will ever be mined or sold. Create your account, secured by Internet Identity today.
- Team:
	- [https://distrikt.io](https://distrikt.io)
	- [https://c7fao-laaaa-aaaae-aaa4q-cai.ic0.app/](https://c7fao-laaaa-aaaae-aaa4q-cai.ic0.app/)
- Dapp:
	- [https://distrikt.app](https://distrikt.app)
	- [https://az5sd-cqaaa-aaaae-aaarq-cai.ic0.app/](https://az5sd-cqaaa-aaaae-aaarq-cai.ic0.app/)
- Twitter: [https://twitter.com/DistriktApp](https://twitter.com/DistriktApp)
- Telegram: [https://t.me/DistriktApp](https://t.me/DistriktApp)
- Newsletter: [https://medium.com/distrikt](https://medium.com/distrikt)

**ICPMeet**

- What: a Tinder on ICP
- Where: [https://www.icpmeet.com/](https://www.icpmeet.com/)
- Who: [Rickey](https://github.com/HelloRickey)
- Twitter: [https://twitter.com/icpmeet](https://twitter.com/icpmeet)
- DFINITY Grant: received in July 2021

**Go Bazzinga**

- What: World's first decentralised "Short-Video X Draft Kings" Social Speculation Platform
- Where: [https://gobazzinga.io/](https://gobazzinga.io/)
- Twitter: [https://twitter.com/GoBazzingainc](https://twitter.com/GoBazzingainc)

**Learned**

- What: LEARND is a community driven educationnal platform running on Internet Computer. We want to provide a new kind of learning and incentives using crypto assets, community vote using SNS, reward learners AND teachers.
- Where: [https://learnd.dedn.eu/](https://learnd.dedn.eu/)
- Twitter: [https://twitter.com/LEARNDTEAM](https://twitter.com/LEARNDTEAM)
- Who: [Charlie Waff](https://twitter.com/WaffCharlie)

**ModClub**

- What: MODCLUB is a decentralized content moderation platform, it simplifies the moderation process by connecting our community to dApps that need UGC moderation. It has a reputation token economics model.
- Where: [https://ljyte-qiaaa-aaaah-qaiva-cai.raw.ic0.app/](https://ljyte-qiaaa-aaaah-qaiva-cai.raw.ic0.app/)
- Who: [Raheel Govindji](https://twitter.com/RaheelGovindji)
- Twitter: [https://twitter.com/ModclubApp](https://twitter.com/ModclubApp)
- Discord: [http://discord.gg/8zUrHd46Tf](http://discord.gg/8zUrHd46Tf)
- Medium: [https://medium.com/@modclub](https://medium.com/@modclub)

**OpenChat**

- What: Decentralized messaging has been a pipe-dream for decades. With the advent of the Internet Computer, real-time messaging is now possible on a blockchain.
- Where: [https://oc.app](https://oc.app)
- Twitter: [https://twitter.com/OpenChat](https://twitter.com/OpenChat)

**Overchute**

- What: A decentralized smart-contract application for crowdfunding the release of intellectual property under open licences
- Where: [https://overchute.com/](https://overchute.com/)
- Twitter: [https://twitter.com/OverchuteApp](https://twitter.com/OverchuteApp)
- Github: [https://github.com/Overchute](https://github.com/Overchute)

## Games (10)

**Cube Run**

- What: The classic game, "Cube Run" gets an update by having a new graphic interface and being hosted completely on-chain. The decentralized version of this game lets you keep your high-score running in your browser through persistent memory. 
- Where: [https://7qx3n-ziaaa-aaaad-qaqca-cai.raw.ic0.app/](https://7qx3n-ziaaa-aaaad-qaqca-cai.raw.ic0.app/)

**HEXGL**

- What: HexGL is a futuristic racing game using HTML5, Javascript, WebGL and hosted on the Internet Computer blockchain in order to run instantly on your browser from anywhere in the world.
- Where: [https://neqb2-dyaaa-aaaad-qameq-cai.raw.ic0.app/](https://neqb2-dyaaa-aaaad-qameq-cai.raw.ic0.app/)

**ICMoji Origins**

- What: ICMoji Origins is an NFT-based multiplayer game built end-to-end on-chain on the Internet Computer. 
- Where:
	- [https://icmojis.com/](https://icmojis.com/)
	- [https://graci-aaaaa-aaaah-aaqjq-cai.raw.ic0.app/](https://graci-aaaaa-aaaah-aaqjq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/icmoji](https://twitter.com/icmoji)
- Who: [Visions](https://twitter.com/Visions_GFX)

**Lo-Fi Player**

- What: Lo-Fi Player is a dapp hosted on the Internet Computer that lets users listen to relaxing beats delivered by blockchain. The back-end is using machine learning to build and develop the AI produced tunes, and users can interact within the player to change the sound to their liking.
- Where: [https://hl2zz-gyaaa-aaaad-qas3a-cai.raw.ic0.app/](https://hl2zz-gyaaa-aaaad-qas3a-cai.raw.ic0.app/)

**Mission Is Possible**

- What: A PVP third person shooter hosted on the Internet Computer blockchain. The John Wick inspired game is built using the Unity 3D Game Engine, and hosted on the IC enabling decentralized login with Internet Identity.
- Where: [https://to3ja-iyaaa-aaaai-qapsq-cai.raw.ic0.app/](https://to3ja-iyaaa-aaaai-qapsq-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/MiP_the_Game](https://twitter.com/MiP_the_Game)

**Reversi**

- What: Reversi is one of the first canister smart contracts deployed to the Internet Computer and is a completely decentralized multiplayer game. Play against a friend (or foe) in real-time, from any browser, anywhere in the world.
- Where: [https://ivg37-qiaaa-aaaab-aaaga-cai.ic0.app/#!/play](https://ivg37-qiaaa-aaaab-aaaga-cai.ic0.app/#!/play)
- Who: [Paul Liu](https://forum.dfinity.org/u/paulliu/)

**Rise of the Magni**

- What: Rise of the Magni, winner of the DSCVR hackathon for games on the Internet Computer. Buy, earn, and trade collectibles, compete in tactical battles online to earn in-game tokens, and venture through story mode to experience one of the first games built on the Internet Computer.
- Where: [https://riseofthemagni.com/](https://riseofthemagni.com/)
- Who: [Toniq Labs](https://igpeu-waaaa-aaaad-qaava-cai.raw.ic0.app/)
- Twitter: [https://twitter.com/ToniqGames](https://twitter.com/ToniqGames)

**Saga Tarot**

- What: Have your fortune told on the Internet Computer. Saga Tarot gives you a tarot reading in one click. The user-friendly dapp is built completely on the Internet Computer, accessible from any browser. What will the future hold for you?
- Where: [https://5nl7c-zqaaa-aaaah-qaa7a-cai.raw.ic0.app/](https://5nl7c-zqaaa-aaaah-qaa7a-cai.raw.ic0.app/)

**Texas Hold'em**

- What: IC Texas Hold'em is a dapp hosted completely on-chain on the Internet Computer. 2nd place winner of the DSCVR Hackathon Season 2
- Where: [https://lm5fh-ayaaa-aaaah-aafua-cai.ic0.app/](https://lm5fh-ayaaa-aaaah-aafua-cai.ic0.app/)
- Who: [NNSDao](https://twitter.com/NnsDaos)
- Github: [https://github.com/NnsDao/ICTexas-UI](https://github.com/NnsDao/ICTexas-UI)

**Welcome Into the Metaverse**

- What: Prize winner of the DSCVR hackathon for the Internet Computer – this game brings digital community into a unified virtual space. Find anecdotes from founding ecosystem members, and go through a series of quests.
- Where: [https://lc7ip-3iaaa-aaaah-aafva-cai.ic0.app/](https://lc7ip-3iaaa-aaaah-aafva-cai.ic0.app/)
- Who: [https://twitter.com/ThuillierSbast3](https://twitter.com/ThuillierSbast3)

## Metaverse (3)

**Drip.Land**

- What: Open project, liquid democracy/community. Metaverse building on the #IC
- Where: https://drip.land/info
- Twitter: [https://twitter.com/ICdripland](https://twitter.com/ICdripland)
- Telegram: [https://t.me/icdrip](https://t.me/icdrip)
- Discord: [https://discord.com/invite/U8YppXuU2x](https://discord.com/invite/U8YppXuU2x)
- Github: [https://github.com/FloorLamp/drip-land](https://github.com/FloorLamp/drip-land)

**Metaverse AI**

- What: Digital human and virtual idol on IC
- Where: [https://www.metaverseai.org/](https://www.metaverseai.org/)
- Who: [Henry Yan](https://www.linkedin.com/in/henryonline/)
- Twitter: [https://twitter.com/metaverseOrg](https://twitter.com/metaverseOrg)
- Github: [https://github.com/Vera-AI-Technology](https://github.com/Vera-AI-Technology)
- DFINITY Grant: received in October 2021

**XR Foundation**

- What: an open source zero-profit collective building metaverse technologies.
- Where: [https://www.xrfoundation.io/](https://www.xrfoundation.io/)
- Github: [https://github.com/XRFoundation/XREngine](https://github.com/XRFoundation/XREngine)

## Productivity (8)

**Aedile**

- What: Aedile brings your team’s work together in one shared space, completely built on-chain. Manage your boards, columns & cards to transform your projects, serving web experiences directly from the Internet Computer blockchain.
- Where: [https://eemeo-taaaa-aaaad-qakjq-cai.ic.fleek.co/](https://eemeo-taaaa-aaaad-qakjq-cai.ic.fleek.co/)
- Who: [Esens Consulting](https://www.esensconsulting.com/)
- Twitter: [https://twitter.com/aedile_ic](https://twitter.com/aedile_ic)

**Bunchd**

- What: Create, Collaborate, and Earn on the Subscription Platform controlled by Creators.
- Twitter: [https://twitter.com/GetBunchd](https://twitter.com/GetBunchd)

**IC Drive**

- What: A decentralized private file storage dapp built on the Internet Computer. Store and securely share any type from anywhere in the world with this decentralized version of Box, or Google Drive.
- Where: [https://icdrive.co](https://icdrive.co)
- Who: [https://twitter.com/nanditmehra](https://twitter.com/nanditmehra)
- Twitter: [https://twitter.com/icDrive](https://twitter.com/icDrive)

**DeckDeckGo**

- What: An open source web editor for presentations built completely on-chain. This dapp is like a decentralized version of Google Slides built on the Internet Computer.
- Where: [https://deckdeckgo.com](https://deckdeckgo.com)
- Who: [https://twitter.com/daviddalbusco](https://twitter.com/daviddalbusco), [https://twitter.com/nasmattia](https://twitter.com/nasmattia)
- Twitter: [https://twitter.com/deckdeckgo](https://twitter.com/deckdeckgo)
- Github: [https://github.com/deckgo/deckdeckgo](https://github.com/deckgo/deckdeckgo)

**Dmail.ai**

- What: Use Web3, not Gmail. Dmail makes it safe and private for you to communicate storage and transfer token & NFTs on DFINITY
- Where: [https://dmail.ai/](https://dmail.ai/)
- Twitter: [https://twitter.com/dmailofficial](https://twitter.com/dmailofficial)
- Telegram: [https://t.me/dmailofficial](https://t.me/dmailofficial)
- Medium: [https://medium.com/@dmail_official](https://medium.com/@dmail_official)
- Github: [https://github.com/dmailofficial](https://github.com/dmailofficial)

**IC Contacts**

- What: A social media management tool build on ICP, helping users manage relations in Web3 networks
- Who: [Relation Labs](https://twitter.com/relationlabs)
- Twitter: [https://twitter.com/relationlabs](https://twitter.com/relationlabs)
- Other: [Grand Slam winner of 7th Wanxiang Blockchain Hackathon](https://twitter.com/herbertyang/status/1454780835379384326)

**Nuance**

- What: Nuance is a Web3.0 blogging platform that is hosted on-chain end-to-end on the Internet Computer. Developed by Aikin Dapps, the alpha of the world’s first blogging platform to be hosted entirely on a blockchain has now launched. Nuance aims to bring NFTs into the world of editorial content ownership.
- Where: [https://fxnaj-yaaaa-aaaaf-qad3q-cai.ic0.app](https://fxnaj-yaaaa-aaaaf-qad3q-cai.ic0.app)
- Who: [AIKIN](https://www.aikin.io/)
- Twitter: [https://twitter.com/AikinDApps](https://twitter.com/AikinDApps)
- Discord: [https://discord.gg/2dPCPu6zxz](https://discord.gg/2dPCPu6zxz)

**Waterslide.app**

- What: Frontend to interact with the @LiquityProtocol
- Where: [https://waterslide.app/](https://waterslide.app/)
- Twitter: [https://twitter.com/waterslide_app](https://twitter.com/waterslide_app)

## Communities (4)

**DfiStarter**

- What: The first project accelerator on Dfinity, providing fund raise, PR&Marketing, tech support to projects on Dfinity
- Where: [https://dfistarter.io/](https://dfistarter.io/)
- Twitter: [https://twitter.com/DfiStarterPad](https://twitter.com/DfiStarterPad)
- Telegram: [https://t.me/DfiStarterPublish](https://t.me/DfiStarterPublish)

**ICP123**

- What: Find Awesome Dfinity Projects
- Where: [https://icp123.xyz/](https://icp123.xyz/)
- Twitter: [https://twitter.com/icp123xyz](https://twitter.com/icp123xyz)
- Github: [https://github.com/icpfans-xyz](https://github.com/icpfans-xyz)
- Who: [Lee](https://github.com/includeleec) of [https://www.nebulas.io/](https://twitter.com/nebulasio)
- DFINITY Grant: received in June 2021

**Internet Computer Education**

- What: very helpful Github-based education resources  with elaborate and step-by-step online classes and cirriculum to teach developers Internet Computer
- Where: [https://github.com/DFINITY-Education](https://github.com/DFINITY-Education)
- Who: [nico](https://github.com/nzoghb), [csolimano](https://github.com/csolimano) and [Claudio Russo](https://github.com/crusso)

**THUBA Education**

- What: THUBA Education is an education platform supported by Tsinghua University student Blockchain Association. The goal is to be a solid bridge between students and blockchain world. The students can use this platform to learn blockchain courses, join Hackthon and do some research. 
- Where: [https://thublockchain.org/](https://thublockchain.org/)
- Who: Tsinghua University Students Blockchain Association

## Enterprise (8)

**Agryo**

- What: Agryo is the global risk intelligence provider that enables financial institutions to assess and manage financial risks in the crop field level for underwriting agriculture insurance, loans, and trade finance globally; as well as meet sustainability goals.
- Where: [www.agryo.com](www.agryo.com)
- Twitter: [https://twitter.com/agryo_](https://twitter.com/agryo_)

**ContentFly**

- What: Marketplace app connecting high quality Content Creators to Brands, running on Dfinity Internet Computer
- Where: [https://contentfly.app/](https://contentfly.app/)
- Twitter: [https://twitter.com/ContentFlyApp](https://twitter.com/ContentFlyApp)

**dFlow**

- What: "decentralized Workflow"- an innovative and simple way for defining and executing cross-organisational business flows
- Where: [https://www.dcentra.io/](https://www.dcentra.io/)

**dService**

- What: A next-generation decentralized Service Management Application running on the Internet Computer. The Application is primarily focused on IT Service Management.
- Where:
	- [https://agnoo-nqaaa-aaaah-aaq4q-cai.ic0.app/](https://agnoo-nqaaa-aaaah-aaq4q-cai.ic0.app/)
	- [https://dservice.app](https://dservice.app)
- Twitter: [https://twitter.com/dServiceApp](https://twitter.com/dServiceApp)

**Optex**

- What: Optex is a powerful data visualisation tool designed to provide seamless insights into complex data. Optex is out-of-the-box solution that will allows users to combine data in a single analysis and get a holistic view of the same with interactive customisable visualisations.
- Where: [https://www.clinicaltrialsintelligence.org/](https://www.clinicaltrialsintelligence.org/)
- Twitter: [https://twitter.com/ClinTexCTi](https://twitter.com/ClinTexCTi)

**Origyn**

- What: The Origyn Foundation is blending luxury goods, with NFTs by providing digital verifications for physical objects. Only possible on the Internet Computer.
- Where: [https://www.origyn.ch/](https://www.origyn.ch/)
- Twitter: [https://twitter.com/ORIGYNTech](https://twitter.com/ORIGYNTech)
- Telegram: [https://t.me/origynfoundation](https://t.me/origynfoundation)

**Triip**

- What: Triip  is a blockchain-enabled travel platform allows for direct interactions between service providers and clients. Using a propriety token, Triip Miles or TIIM,  Triip  is a network that enables greater transparency, security and lower cost transactions between those who travel and those who serve them.
- Where: [https://www.triip.me/](https://www.triip.me/)
- Twitter: [https://twitter.com/triipme](https://twitter.com/triipme)
- Telegram: [https://t.me/TriipMilesICO](https://t.me/TriipMilesICO)
- Github: [https://github.com/triipme](https://github.com/triipme)
- Who: [Triip Pte Ltd](https://www.triip.me/pages/about_us)
- DFINITY Grant: received in Aug 2021

**WeAct.chat**

- What: The app made for groups of advocates, activists, and change makers working to better the world
- Where: [https://www.weact.chat/dfinity](https://www.weact.chat/dfinity)
- Twitter: [https://twitter.com/WeAct_Chat](https://twitter.com/WeAct_Chat)
