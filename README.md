# Taiko Grants Program

View the full grants program description on our mirror blog here: https://taiko.mirror.xyz/G7dmuoR42S4D55vT8bs_lAxPZP63kAgRu2IfqkJdf6U.

We are super excited to announce the launch of Taiko’s first community grants program! 🌍🏗️

The aim of this program is to discover and support innovative community members that build up and build on the Taiko ecosystem, with the financial incentives and developer resources needed to bring their visions to life. Despite still being in our testnet phase we think there is immense value in supporting ambitious builders from Day 0, and allowing them to participate in the network’s potential success. Even more importantly, we see this as a great opportunity to learn more about effective grant frameworks and outcomes, so that we can iterate and improve our future grants programs together with you.

In the post below, we will cover some of the most relevant points of the program, and also provide you with some guidance on the areas that we are particularly excited about.

As with everything we do, we hugely value the feedback of our community, so please do let us know your thoughts (or any questions) in our Discord or community forum.

## Grant Program Format
All awarded grants will be in the form of future Taiko tokens, with up to 0.2% of the total token supply allocated to just the inaugural program 👀. These tokens will originate from the treasury, which will eventually be owned and managed by the Taiko DAO. Until the DAO is established, the team and/or foundation will oversee the treasury. While the total allocation of tokens to future grant programs is still to be determined, we expect it to be significantly higher than what is available in this round.

### Distribution and Vesting
Any awarded grants will remain valid for up to 6 months and will come with milestones (2-month intervals) which determine the vesting schedule of the grant tokens. Should a project exceed the 6-month timeframe, it forfeits any remaining grant funds, and the remaining tokens will be reallocated to other grant initiatives. However, projects that applied to or received any grants, may still apply and qualify for future Taiko grant opportunities. As a matter of fact, we actively encourage past grantees to continue to apply to future programs, i.e., there is no downside to applying as early as possible.

All vested tokens will also observe a 6-month lock-up period, which commences at the Token Generation Event (TGE) or upon milestone fulfillment — whichever comes later. In addition, we will ask our grantees to demonstrate their deliverables primarily in open-source code and to deploy usable prototypes on Taiko’s testnets.

### Project Guidelines
Our project guidelines advocate for transparency and cooperative growth. As such, we require that:

Unless explicitly stated, all smart contracts and frontend code be open-sourced from the project's inception.

Projects involving dApps must choose Taiko as one of their very first platforms, but they can also deploy and integrate on other L1/L2/L3s. That said, we do look favorably upon Taiko-tailored projects, i.e., those that truly take advantage of Taiko’s strengths and design decisions, such as Ethereum-equivalence and permissionless proposing and proving.

Taiko Labs or its associated entities receive the right to invest up to $250K USD in any project’s subsequent fundraising round, up to one-year post-grant acceptance (if applicable).

Grantees can apply for grants from other projects, given all other requirements are met.

Grantees and Taiko must establish a formal legal agreement detailing the expectations and responsibilities of both parties. Before execution of the agreement, discretion for changes in the program rest exclusively with Taiko.

If you are awarded a grant, you may not disclose this (incl. any details such as the number of vested or received tokens) until we have done so.

Note that eligible projects can be in the early ideation stage, active development stage, or in mature operational stage, looking to make meaningful contributions to Taiko.

### Application Process
Applications should be submitted by filling in the template issue in this GitHub repo.

Please be as detailed as possible when filling out the form and focus on areas such as the background of core team members, technical design and integration with Taiko, and any product roadmaps (if available).

The application window is open from now until August 31st, 2023. The team will continuously review all applications and be in touch with shortlisted projects to ask further questions, set up interviews or approve their submission. We may reach out or approve applicants on a rolling basis, and will have reached final decisions by two weeks after the submission deadline. We will also announce the winning projects via our official public channels.

Please note that while our aim is to streamline the process and minimize stringent requirements, we reserve the right to adjust the criteria or delay decisions should the application volume become overwhelming.

## Categories
While Taiko is a general-purpose ZK rollup and we welcome all kinds of applications, there are a few areas that get us particularly excited and giddy 💗. To help get our builders thinking about creative solutions, we have therefore shared them below.

**1. Zero-Knowledge Proofs (ZKP)**
Why we’re excited: well, it’s really no secret that we love ZK, and hence we are very keen to promote any advancements in this space!

Our current focus lies in the following areas:

Circuit Optimizations: we are seeking projects that strive to reduce proving times and hardware requirements. This focus area aims to curtail costs and latency, leading to more cost-effective and efficient ZK-EVMs.

Prover Optimizations: where the goal is to explore optimization opportunities within a variety of hardware systems, including CPU, GPU/FPGA/ASIC, and memory. Enhancements in this area have the potential to significantly boost the performance of provers within ZK-EVM systems.

Next-Generation Proving Systems: currently, the proving system utilizes turbo plonk, but the program is eager to explore new proving systems, like Nova. Any project that aids in the transition to these novel systems can help alleviate bottlenecks present in the existing ZK-EVM.

Circuit Writing Tools Improvements: we look for projects that simplify and improve circuit writing. This will directly contribute to the efficiency and readability of the code, thereby enhancing the success of ZK-EVMs.

Testing Improvements: given the complexity of a ZK-EVM, rigorous testing is necessary to ensure its robust functionality. Therefore, projects that broaden testing capabilities and improve the overall quality assurance process are highly encouraged.

ZK-Specific Applications: showing interest in how ZK technology can be applied to enhance functionality in areas like bridges, privacy, and identity. Projects that challenge the boundaries of these ZK-specific applications could foster unprecedented innovation in the field.

**2. Proposer Optimization**
Why we're excited: Taiko being a permissionless based-rollup allows any address to build and propose an L2 block directly on L1, without going through an off-chain (Ethereum) proposer selection or block selection process. This means that multiple proposers may be building blocks in parallel, resulting in duplicated effort and wasted gas. One way of solving this is by hooking into Ethereum’s PBS. However, this is only one possible solution, and there are many other aspects that require a well-thought-out approach, like the impact of variable L1 gas costs and prover cost, and L2 transaction price prediction. We look forward to seeing innovative approaches that seek to solve or mitigate this issue.

3. Alternative Proposer-Prover Tokenomics
Why we're excited: the intricacies and challenges of L2 tokenomics design have proven to be more engaging and complex than we initially anticipated. We've experimented with two designs across our three testnets. These iterations featured auto-adjustments of fees and rewards per gas or per block. Additionally, we attempted a third design based on batch auctions but subsequently decided not to pursue it. Currently, we are testing a fourth design premised on token staking.

While we recognize that no perfect L2 tokenomics solution exists, we are eager to explore innovative designs brought forth by community developers. We remain open to incorporating these promising concepts into our code, continuously improving and evolving.

We have laid out our design objectives and a set of metrics to evaluate L2 tokenomics for Taiko in this document.

**4. Proof Markets**
Why we're excited: in the latest update to Taiko's tokenomics, provers have the ability to stake Taiko tokens and designate an expected rewardPerGas for proving, thereby securing an exclusive chance to prove a block. Given that such tokenomics are executed via smart contracts on L1, only the top 32 provers are supported.

We understand that smaller and solo provers may not possess the required quantity of tokens to successfully compete in the staking contest, or they might lack the infrastructure to ensure redundant prover capacity and meet proving deadlines. Consequently, they may need to join secondary, off-chain proof markets to contribute proving capacity without directly interacting with the tokenomics on-chain.

We look forward to seeing the open-source community's innovative designs and developments for a proof market infrastructure that will empower these small and solo provers.

**5. Social/Messaging dApps**
Why we're excited: Taiko's L2/L3 solutions are uniquely positioned to facilitate low-value transactions. We believe that social network and messaging applications are particularly compatible with Taiko's L2 and L3 solutions, owing to their permissionless and decentralized nature — a distinct advantage over many other rollup alternatives. Our goal is to foster an environment where Taiko's L2/L3 solutions serve a larger volume of transactions, emphasizing frequency over individual transaction value.

**6. NFT Bridge & Marketplace**
Why we're excited: conscious that most NFTs may not hold high value, and that trading NFTs within social finance and gaming applications should ideally incur minimal cost, our goal is to cultivate a robust NFT infrastructure on Taiko's L2. We are eager to foster a swift adoption of social finance and gaming dApps, which will ultimately contribute to a more prosperous and diverse ecosystem. This should hopefully open the door to new opportunities for creators and innovators alike. Note that the backend of the marketplace does not need to be open-sourced.

**7. Games**
Why we're excited: gaming represents another category of dApps particularly well-suited for an L2 or even a dedicated L3 environment (with permissioned block proposers but decentralized and permissionless provers). Taiko’s inception layer enables the same Taiko codebase to be deployed on top of a Taiko L2, creating application-specific Taiko L3s (’app-chains’).

Though Taiko's open-source codebase offers a fully permissionless and decentralized zkRollup design, we understand that community developers may need to introduce specific centralized controls to tailor the app chain to their dApps' needs. We believe this flexibility is one of Taiko's key strengths, opening new avenues for innovation and game development.

**8. AI Integration**
Why we're excited: AI really excites us as it heralds a new era in the blockchain landscape. Combining AI with blockchain could result in unprecedented efficiencies, superior security, and enhanced user experiences. AI can automate complex tasks, improve decision-making, and offer personalized solutions, transforming the way we interact with blockchains. Moreover, it can add an intelligent layer to core blockchain functionalities like smart contracts, offering advanced data analysis and unlocking new possibilities. We believe the intersection of AI x blockchain can be transformational, so we encourage the community to explore this space.

**9. Education & Community Efforts**
Why we're excited: we believe that educational and community efforts are not only important to raise awareness of Taiko’s unique positioning and design, but also to advance the ZK and crypto space as a whole. Therefore, we actively encourage any initiatives that enhance the communities understanding, either through abstracting complicated topics, creating tutorials, writing technical guides, or anything else really that elevates the collective understanding of users and builders in this space.

**10. Surprise Us**
Why we created this category: we understand that there are always groundbreaking applications and initiatives that exceed our imaginations. We wholeheartedly welcome innovative ideas that may not necessarily align with the categories outlined above. If your application doesn't fit into the existing categories, please don't hesitate to submit it under this category.

## Bridging the Gap
The truth is Taiko (or any blockchain, for that matter) would be nothing without its builders and community, so we see our grantees as integral extensions of the Taiko team. As we transition from Taiko Labs into the Taiko Foundation and Taiko DAO, we expect the line between full-time engineers and community builders to become even more blurry. We believe in the power of the open-source community, particularly Ethereum’s, which is why we welcome all builders who share this vision and believe in a more equitable, permissionless, and transparent future.

In conjunction with launching this grants program, we also seek to experiment with the grant framework itself. That can mean the duration, style, council/decision-making body, and much more is up for experimentation and iteration. For grants, we are only driven by our desire to achieve the best outcomes for the Taiko network — how we get there and who leads the way is something we want to shape together with you and the community.

For now, if you have ideas on grant frameworks, we’d like to have this conversation with you on our community forum. Please share your frameworks — as detailed or brief as you see fit — as responses to the grant thread on our community forum (see link below). These frameworks can look towards the horizon and contemplate Taiko grants programs when the Taiko DAO is in control.

## Next steps? 📣
Submit a request for grant (RFG) via our [GitHub form](https://github.com/taikoxyz/grants/issues/new?assignees=dantaik%2Cd1onys1us%2C2manslkh%2CMarcusWentz%2Cmfinestone&labels=grant%2Capplication&projects=&template=grant_form.yml&title=Awesome+Project+Name)!

Share your feedback via our forum thread, or reach out to us at grants@taiko.xyz
