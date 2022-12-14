# Open Grant Proposal: `GIRAF - IPFS based legislation system`

**Name of Project:** `GIRAF - IPFS based legislation system`

**Proposal Category:** `app-dev`

**Proposer:** [`@slonigiraf`](https://github.com/slonigiraf/)

**Do you agree to open source all work you do on behalf of this RFP and dual-license under MIT, APACHE2, or GPL licenses?:** `Yes`

# Project Description

Laws are a fundamental part of human civilization and are generally understood to be a set of instructions or rules that people have agreed to follow. Examples of laws include the Bill of Rights in the United States, the Wikipedia article on DNA, history schoolbook, and the balance of a specific bitcoin wallet. However, the exact definition of the term "law" is a matter of debate. In this document, we will use the above definition for the purposes of our discussion.

The process of lawmaking is closely tied to economic activity. For example, politicians in the United States often rely on [funding from lobbyists](https://en.wikipedia.org/wiki/Lobbying_in_the_United_States) to run for office and push for legislation that benefits those lobbyists. Similarly, editors of Wikipedia articles may spend their valuable time and resources [fighting for the content](https://en.wikipedia.org/wiki/Wikipedia:Edit_warring) of an article, and the author of a schoolbook or a publishing house may receive funding from individuals or groups who wish to promote [their point of view](https://meduza.io/feature/2019/10/21/ministerstvo-prosveschenie). In the case of Bitcoin, miners [are paid](https://bitcoin.org/bitcoin.pdf) for their work in changing the balances of wallets. In some cases, foreign countries may even intervene in the lawmaking process of another country [with money](https://www.reuters.com/article/politicsNews/idUSN2450753720071024).

It can be argued that the practice of buying and selling laws, also known as lobbying, is a global norm that is generally accepted and serves as an important tool for creating consensus in society. This in turn can lead to economic well-being, as seen in the United States with its well-established lobbying practices.

**We plan to build a system on top of IPFS/Filecoin** that allows the **creation and lobbying of laws** in groups if different size: from small communities to a size of a country. It will be used in groups that lack legislation due to the small size of a group or in bigger societies to speedup the creation of a public consensus.

The proposed system would involve the use of a database to store entries for each law, with each entry containing:

- A unique identifier for the law, such as a serial number.
- A hash of the text of the law, which could be generated using a system such as the [IPFS](https://ipfs.tech/).
- The amount of money that was used for a lobbying when the law was created.

The use of hashes for the text of laws would allow for the efficient storage of laws using a system like IPFS/Filecoin, while also providing protection against unauthorized changes to the text of the laws.

Our system will also include the user interface for such a database.

## Value

The use of Filecoin in the GIRAF system could potentially lead to increased demand for Filecoin storage and raise awareness of the platform. The GIRAF project could help showcase the potential uses of Filecoin and the benefits of decentralized systems. By providing a successful example of a decentralized system in action, the GIRAF project could help raise awareness of Filecoin and potentially attract more users and developers to the platform.

The GIRAF project code will be extensively used in our main project, [Slonigiraf](https://github.com/slonigiraf/whitepaper/blob/main/slon/ENG.md), which is a tool designed for the creation of digital recommendation letters and diplomas. The essence of the lawmaking process is the coordination of various companies and educational organizations in determining the skills that need to be assessed and the appropriate methods of assessment for those skills.

We are faced with the challenge of creating a user experience that is simple and intuitive for people who may not be familiar with our system. We are working hard to design a user interface that is easy to understand and use, even for those with no prior knowledge or experience with decentralized systems or blockchain technology.

## Deliverables

The GIRAF project will include the following components:

- A Typescript library for storing laws on IPFS/Filecoin, along with an API for registering them on a blockchain
- React components for creating, representing, and canceling laws
- An example website that demonstrates the use of the technology for creating, representing, and canceling laws
- A paper that describes how to use the technology from the perspectives of both developers and users

Together, these components will provide a comprehensive solution for creating, storing, and managing laws using decentralized technology.

## Development Roadmap

### Milestone 1: Working backend and APIs

*Deliverables:*

- A Typescript library for storing laws on IPFS/Filecoin.
- API for registering them on a blockchain

*People Involved:*

- 2 software engineers
- 1 project manager

*Expected Hours:* 127

*Expected Days:* 14

*Expected Budget:* $7,500 USD

### Milestone 2: Frontend modules

*Deliverables:*

- React component for creating law
- React component for representing law
- React component for canceling law

*People Involved:*

- 2 software engineers
- 1 project manager

*Expected Hours:* 170

*Expected Days:* 21

*Expected Budget:* $10,000 USD

### Milestone 3: Example usage and documentation creation

*Deliverables:*

- An example website that demonstrates the use of the technology for creating, representing, and canceling laws
- A paper that describes how to use the technology from the perspectives of both developers and users

*People Involved:*

- 3 software engineers
- 1 project manager

*Expected Hours:* 212

*Expected Days:* 28

*Expected Budget:* $12,500 USD

## Total Budget Requested

Total: $30,000 for the development of the GIRAF - IPFS based legislation system for communities.

This sum will support three current software developers and 1 project manager. Also we plan to spend a small part on infrastructure: a server lease.

Breakdown of the budget:

- Salary: 95%.
- Operations: 5%.

## Maintenance and Upgrade Plans

Maintenance for 1 year guaranteed, including critical bug fixes on demand. We are always open to community suggestions to improve the project.

# Team

## Team Members

- Denis Reshetov - Founder, Rust/JavaScript developer
- Ilya Moskvin - JavaScript developer
- Aleksey Pastutsan - Rust/JavaScript developer
- Natalie Andreeva - Project manager


## Team Member LinkedIn Profiles

- [Denis Reshetov](https://www.linkedin.com/in/reshetovdenis/)
- [Ilya Moskvin](https://www.linkedin.com/in/ilya-moskvin-02794b22b/)
- [Aleksey Pastutsan](https://www.linkedin.com/in/aleksey-pastutsan-a07ab2158/)
- [Natalie Andreeva](https://www.linkedin.com/in/natalie-andreeva-4a250b56/)

## Team Website

- [Project whitepaper](https://github.com/slonigiraf/whitepaper/blob/main/giraf/ENG.md)
- [Company site](https://slonigiraf.org/)

## Relevant Experience
Denis Reshetov is a highly skilled and dedicated full-stack developer and [scientist](https://pubmed.ncbi.nlm.nih.gov/?term=reshetov+d). He has a passion for building tools for decentralized society, and his leadership skills have proven invaluable in guiding teams to successfully complete complex projects. For example, he recently received a grant from the Web3 Foundation for a project [that he successfully completed](https://github.com/w3f/Grants-Program/blob/master/applications/slonigiraf.md). In addition to his technical expertise, Denis is known for his ability to motivate and inspire his team members. He has a clear vision for the projects he works on, and he is able to effectively communicate that vision to his team in a way that encourages [collaboration and fosters a sense of shared purpose](https://pubmed.ncbi.nlm.nih.gov/35039573/).

Ilya Moskvin is a highly skilled JavaScript developer with a wealth of experience in building complex ERP systems. He has a [deep understanding of the web3 stack](https://github.com/iamoskvin/), and he has been instrumental in developing applications in the Ethereum space over the last two years. He is a strong communicator and is always willing to help his colleagues whenever they need it. His positive attitude and his commitment to excellence make him a pleasure to work with and a valuable contributor to the project.

Aleksey Pastutsan has [decades of experience](https://github.com/almipa) in software engineering, and his current focus is on web3 projects based on the Typescript/Rust stack. He is a highly skilled developer with a wealth of knowledge and expertise in the field. Aleksey's expertise in web3 technology and his ability to create robust, scalable solutions make him an invaluable member of the  project. His dedication to advancing the field of decentralized technology and his passion for building tools that can improve the lives of people around the world make him a valuable asset to our team.

Natalie Andreeva is a highly experienced financial manager with a background in fintech. She has a proven [track record](https://www.linkedin.com/in/natalie-andreeva-4a250b56/) of successfully organizing and coordinating teams working on specific projects, and she is skilled at allocating resources and managing people in order to achieve project objectives. Natalie's expertise in financial management and her ability to effectively coordinate teams make her an invaluable member of the project.

## Team code repositories

- [Main repository](https://github.com/slonigiraf/)
- [Typescript library to sign recommendation letters and store them on IPFS](https://github.com/slonigiraf/helpers)
- [Rust module for recommendation letter issuing](https://github.com/slonigiraf/recommendation-letter)
- [React example UI for recommendation letter issuing](https://github.com/slonigiraf/recommendation-letter-example-ui)
- [Full functional UI for recommendation letter issuing](https://github.com/slonigiraf/slonigiraf-front-end)
- [Blockchain for recommendation letter issuing](https://github.com/slonigiraf/recommendation-letter-example-node)

# Additional Information
**How did you learn about the Open Grants Program?** `From searching for grants in web3 field`

**Email address for discussing the grant agreement and general next steps:** `reshetovdenis@gmail.com`