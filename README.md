Scaffold Stylus
Funding Ask

25,000 USD

Submitted on

01 May, 2025

Milestones

3

Category

Stylus

Details

Scaffold Stylus is a open-source toolkit that simplifies Arbitrum Stylus development through battle-tested patterns evolved from our work contributing Scaffold-ETH and creating Scaffold-Stark. We're building the definitive environment for Rust/C++ smart contract development on Arbitrum.
Key features:
Advanced Contract Hot Reload: Real-time frontend adaptation to Stylus contracts (Rust/C++) with type-safe binding generation
Comprehensive Testing Suite: Integrated unit, integration, and end-to-end testing optimized for Stylus' WASM-based execution environment
One-Command Deployment: Frictionless deployment across local Nitro dev node, testnet, and Arbitrum mainnet(Arbitrum one, nove, orbit chain) with environment-specific configuration
Instant Project Creation: Bootstrap production-ready applications via npx create-stylus@latest base template + 4 templates extension based on most common use cases like DeFi, NFts, Oracles usage, Randomness 
Production-Ready Component Library: Modular, extensively tested UI components and hooks specifically designed for Stylus applications
Vercel Integration: Deploy full-stack dApps with a simple yarn vercel command
Interactive Documentation: Extensive guides with live code examples and step-by-step tutorials
Our toolkit aims to reduce Stylus development time while enabling best practices from day one. By abstracting away infrastructure complexities and providing a streamlined developer experience, Scaffold Stylus will accelerate adoption of Arbitrum's high-performance Stylus environment and expand the ecosystem's developer base.
What innovation or value will your project bring to Arbitrum? What previously unaddressed problems is it solving? Is the project introducing genuinely new mechanisms.

Scaffold Stylus delivers breakthrough value to Arbitrum by creating the first comprehensive development framework specifically optimized for Stylus, addressing critical friction points in the ecosystem:
Unaddressed Problems We're Solving:

Development Environment Fragmentation: Currently, Stylus developers must cobble together disconnected tools for Rust/C++ contract development, testing, and frontend integration. This fragmentation introduces significant complexity and slows adoption. Scaffold Stylus provides the first unified environment tailored for Dapps Stylus development.
Missing Tooling for Rust/WASM to Web Interfaces: The current ecosystem lacks tooling that seamlessly connects Rust/C++ Stylus contracts with modern web frontends. Our type-safe binding generation and real-time hot reload system solve this fundamental gap.
High Entry Barriers for Non-Solidity Developers: Rust and C++ developers face steep learning curves when entering Arbitrum development. By providing instantly deployable templates and interactive documentation, we dramatically lower barriers for these developers to leverage their existing skills on Arbitrum.
Genuine Innovation:

Rust-Optimized Contract Hot Reload: Contract-to-frontend binding system specifically for Rust/WASM contracts that enables real-time updates as developers modify their contracts. Perfect for debugging contracts
Simple-Command Cross-Environment Deployment Pipeline: Our deployment system introduces a new mechanism for seamlessly deploying the same Stylus application across local development, sepolia testing, and mainnet production environments with automatic configuration adjustments.
What is the current stage of your project.

Ideation + previous proof of successful work

Previous contribution to: https://scaffoldeth.io/
Creators and maintainer of: https://scaffoldstark.com/ , https://speedrunstark.com/ , https://github.com/Scaffold-Stark
Do you have a target audience? If so, which one.

Primary Audiences:

Rust/C++ Developers New to Blockchain: Experienced systems programmers who want to leverage their existing skills on Arbitrum without learning Solidity. These developers possess deep technical capabilities but need streamlined onboarding to blockchain paradigms.
Existing Solidity Developers Exploring Stylus: Ethereum developers interested in Stylus's performance advantages who need familiar tooling patterns to quickly transfer their skills to Rust/C++ development on Arbitrum.
Web3 Hackthon participants: Teams developing applications whith Stylus's who need to accelerate their development cycle.
Secondary Audiences:

Blockchain Education Programs: Coding bootcamps and university courses teaching blockchain development who need accessible, well-documented environments for students to learn how to build Dapps On Arbitrum with stylus

Enterprise Development Teams: Corporate developers exploring Arbitrum who require production-ready tooling with comprehensive testing capabilities and deployment options.
Open Source Contributors: Community developers who want to contribute to scaffold stylus, build upon or extend a well-structured framework for Stylus development.
Do you know about any comparable protocol, event, game, tool or project within the Arbitrum ecosystem.

Yes, we're aware of Wizard, https://thewizard.app/ - an online IDE inspired by Remix that's designed for Stylus smart contract development. Like Remix for Ethereum, Wizard provides a browser-based environment for testing, building, and deploying Stylus contracts.
While Wizard is an important part of the Stylus ecosystem, Scaffold Stylus differentiates in several significant ways:

Full-Stack Framework vs. Online IDE:

Wizard is primarily an online IDE for contract development
Scaffold Stylus is a complete framework that integrates contract development with frontend applications, testing infrastructure, and deployment pipelines.

Development Environment:
Wizard offers a browser-based development experience
Scaffold Stylus provides a local development environment(you can use VS code) that integrates with developers' existing tools, workflows, and CI/CD systems

Target Use Case:
Wizard excels at quick experimentation and learning
Scaffold Stylus is designed for production application development with complex frontends and complete testing

Complementary Relationship:
We view Wizard as complementary to Scaffold Stylus - developers might use Wizard for initial exploration and prototyping, then move to Scaffold Stylus for full application development.

Our framework fills a distinct niche in the ecosystem by providing the production-ready tooling necessary for building complete dApps on Stylus, while Wizard serves as an excellent entry point for developers to experiment with Stylus contracts.

Have you received a grant from the DAO, Foundation, or any Arbitrum ecosystem related program or conducted any IRL like a hackathon or workshop.

No

Have you received a grant from any other entity in other blockchains that are not Arbitrum.

Team has received recognition through:

Starknet, ICP, Polkadot
What is the idea/project for which you are applying for a grant.

Scaffold Stylus is a comprehensive development framework designed to accelerate building on Arbitrum Stylus. Drawing on our expertise contributing to Scaffold-ETH and creating Scaffold-Stark, we're building a complete toolkit that drastically simplifies the Stylus development workflow with Rust/C++.

Our implementation plan includes 3 phases over 12 weeks:
Phase 1: Core Architecture (Weeks 1-4)

Establish monorepo structure integrating Rust/TypeScript
Implement local Nitro node with automated setup
Build type-safe binding generation system
Create UI/UX Design for landing page and scaffold-stylus toolkit
Phase 2: Development Experience (Weeks 5-8)

Implement real-time contract hot reload for Rust contracts
Develop React component library with Stylus-specific hooks
Create testing optimized for Stylus execution
Build deployment pipeline for sepolia testnet and Arbitrum one mainnet
Launch public scaffold-stylus toolkit beta version and Landing page
Phase 3: Templates and Documentation (Weeks 9-12)

Create npx create-stylus@latest CLI bootstrapping tool for base template creation
Create starter templates for common dApp patterns via extensions to the base template. Initially providing 4 extensions:
npx create-stylus@latest -e erc-20. Introduces an ERC-20 token contract and demonstrates how to interact with it, including getting a holder balance and transferring tokens.
npx create-stylus@latest -e erc-721. Introduces an ERC-721 token contract and demonstrates how to use it, including getting the total supply and holder balance, listing all NFTs from the collection and NFTs from the connected address, and how to transfer NFTs.
npx create-stylus@latest -e chainlink-data-feed. Basis for your Chainlink based dApp or project. This extension includes Data Feeds, price feeds.
npx create-stylus@latest -e chainlink-vrf. Chainlink based dApp or project with Chainlink verified randomness.
Support deployment to Arbitrum Nova and Orbit chain
Develop comprehensive documentation with examples
Implement Vercel integration for frontend deployment
Launch public alpha with developer workshops and official scaffold-stylus website https://scaffoldstylus.com/
Outline the major deliverables you will obtain with this grant.

1.Public GitHub Repository

Production-ready codebase with CI/CD integration
Contribution guidelines and community standards
MIT license. Open source
2.Project Creation System

NPX package for instant project setup
Base template + 4 template extension for different application types
Configuration system for different development environments
3.Website of scaffold stylus

Figma design of website/portal for scaffold stylus and UI for scaffold stylus toolkit.
Create a website/portal for scaffold stylus.
Landing page showing all the features of scaffold stylus
Provide a url: http://scaffoldstylus.com/
4.Documentation & Educational Resources

Interactive tutorials with code examples
Walkthroughs of development workflows
Best practices guides for Stylus development
Deployed demo for live interaction
Please explain how your idea/project aligns with the Arbitrum ecosystem goals.

Scaffold Stylus directly supports Arbitrum's ecosystem goals in several key ways:

First, it addresses the developer tooling by creating a specialized framework for Stylus. This fills a critical gap in the current ecosystem where developers lack integrated tooling for the full development lifecycle with Rust/C++ contracts.

Second, Scaffold Stylus will dramatically expand the potential developer base for Arbitrum by making the platform accessible to the vast community of Rust and C++ developers who haven't previously built blockchain applications. This represents a significant growth opportunity beyond the existing Solidity developer community.

Third, by reducing development time and complexity for Stylus applications, our framework will enable more teams to leverage Stylus's performance advantages. This will result in more sophisticated, high-performance applications that showcase Arbitrum's unique capabilities compared to other L2 solutions.

Finally, Scaffold Stylus provides a foundation for educational initiatives and community growth. By lowering the learning curve for Stylus development, we'll enable more effective developer onboarding programs and workshops, directly supporting Arbitrum's goal of expanding developer relations activities.

What is your requested grant.

25000 USD

Website.

na

Please provide a detailed breakdown of the budget in term of utilizations, costs and other relevant information.

https://docs.google.com/spreadsheets/d/1n1yfRFRHJsmY3HrYUWTbwZKmip4hhBh6DaSkKOKgPN0/edit?usp=sharing

Provide a list of the milestones, with the USD amount of the grant associated to it, the deliverables that will be provided, and the estimated completion time.

Milestone 1: Core Architecture & Foundation (Weeks 1-4) - $8,000
Deliverables:

GitHub repository with monorepo structure and CI/CD setup
Local Nitro development node integration with automated configuration
Type-safe binding generation system between Rust contracts and TypeScript
Figma designs for Scaffold Stylus landing page and toolkit UI/UX
Initial project structure Estimated completion: End of Week 4
Milestone 2: Development Experience (Weeks 5-8) - $9,000
Deliverables:

Real-time contract hot reload system for Rust/Stylus contracts
React component library with Stylus-specific hooks
Testing framework optimized for Stylus execution environment
Deployment pipeline for sepolia testnet and arbitrum one mainnet environments
Beta version launch of Scaffold Stylus toolkit
Deployment of initial landing page at scaffoldstylus.com
Host a session IRL in one of our hub ( Singapore - Vietnam or China ) and provide feedback from developers directly to the DAO Estimated completion: End of Week 8
Milestone 3: Templates and Documentation (Weeks 9-12) - $8,000
Deliverables:

npx create-stylus@latest CLI bootstrapping tool
Collection of starter templates for common dApp patterns. Base template(npx create-stylus@latest) + 4 extensions: erc-20, erc-721, chainlink-data-feed, chainlink-vrf,
Comprehensive documentation with interactive examples
Vercel integration for one-command frontend deployment
Deployment pipeline for arbitrum nova and orbit chain environments
Full public alpha release with complete website
Developer workshops and community onboarding materials
Live demo application showcasing framework capabilities Estimated completion: End of Week 12 Total Grant Amount: $25,000
Are milestones clearly defined, time-bound, and measurable with quantitative metrics where applicable? What are your reference KPI, if applicable, for each milestone.

Milestone 1: Core Architecture & Foundation ($8,000) - Weeks 1-4
KPIs:

Repository structure completeness (80% of planned components)
Binding generation successful for Stylus contracts
Successful Local Nitro devnet integration
80% of planned UI/UX designs completed and approved
80% test coverage for core binding generation system Deliverables: GitHub repository, Nitro integration, binding system, UI/UX designs Completion: End of Week 4
Milestone 2: Development Experience ($9,000) - Weeks 5-8
KPIs:

Hot reload system updates UI within 3 seconds of contract changes
React component library implements 10+ Stylus-specific components
Testing framework achieves 85%+ code coverage
Deployment pipeline successfully deploys to sepolia testnet and arbitrum one mainnet in <2 minutes
Beta version used by 10+ early testers
Landing page relased.
Host a session IRL in one of our hub ( Singapore - Vietnam or China ) and provide feedback from developers directly to the DAO Deliverables: Hot reload system, component library, testing framework, deployment pipeline, beta toolkit, landing page Completion: End of Week 8
Milestone 3: Templates and Documentation ($8,000) - Weeks 9-12
KPIs:
-Repository structure completeness (100% of planned components)
-1000% test coverage for core binding generation system

Deployment pipeline successfully deploys to arbitrum nova mainnet and orbit chains in <2 minutes
CLI tool creates new projects in <30 seconds
4+ starter templates covering common use cases
Documentation achieves 100%+ coverage of framework features
20+ developers onboarded through post/workshops
20+ GitHub stars within first week of public release
Demo application successfully showcases all core features
Live website with latest UI version Deliverables: CLI tool, templates, documentation, Vercel integration, public alpha, workshops, demo app Completion: End of Week 12
What is the estimated maximum time for the completion of the project.

up to 4 months in case of delays

How should the Arbitrum community measure the success of this grant.

1.Developer Adoption

Number of GitHub stars, forks, and active contributors
Monthly active users of the framework (tracked via npm downloads)
Number of projects built using Scaffold Stylus (identified via package dependencies)
2.Ecosystem Impact

Increase in Stylus contract deployments on Arbitrum following framework release
Diversity of applications built using scaffold stylus (DeFi, gaming, infrastructure, etc.)
Number of new developers entering the Arbitrum ecosystem via Scaffold Stylus
3.Technical Performance

Development time reduction compared to vanilla Stylus development (via developer surveys)
Quality of applications built (code quality metrics, security audits)
4.Community Engagement

Workshop attendance and community event participation
External community driven workshops that uses scaffold stark as tool to teach stylus
Documentation usage statistics
Community forum/Discord activity related to Scaffold Stylus
What is the economic plan for maintaining operations or continuing the growth of your project after the grant period.

1.Open Source Community Development

Establish a core maintainer team with clear contribution guidelines
Actively recruit contributors from the Arbitrum ecosystem
2.Strategic Partnerships

Partner with key Arbitrum ecosystem projects to ensure ongoing compatibility
Collaborate with educational platforms to integrate Scaffold Stylus into blockchain development courses
3.Ongoing Development

Apply for follow-on grants for specific feature expansions
Establish Open source contribution programs for feature development
Create a sustainable release schedule with regular maintenance updates
4.Community Building

Regular developer meetups and workshops
Case study development showcasing successful applications
Market Needs: For developers building apps and interfaces, what specific challenges or opportunities do they face in Arbitrum.

Market Needs: For developers building apps and interfaces, developers on Arbitrum face several specific challenges and opportunities, particularly when using Stylus:

Challenges:

Fragmented Development Environment: There's no unified framework integrating Stylus's Rust/C++ contracts with modern frontend development, forcing developers to cobble together disparate tools.
Language Barrier: Rust and C++ developers face a steep learning curve when entering Arbitrum development without specialized tooling that bridges blockchain concepts with systems programming paradigms.
Complex Deployment Workflows: Deploying across development, testing, and production environments requires significant manual configuration and specialized knowledge of Arbitrum infrastructure.
Limited Real-time Feedback: The development cycle is slowed by the lack of hot-reload capabilities specifically designed for Stylus's Rust/WASM execution environment.
Insufficient Full Dapp Starter Templates: Developers must build common patterns from scratch without access to production-ready Dapp templates optimized for Stylus.
Opportunities:

Untapped Developer Pool: The ability to use familiar languages like Rust/C++ could attract a much larger developer base to Arbitrum if proper tooling existed.
Cost Efficiency: Developer experience can be much better, but developers need frameworks that help optimize this advantage automatically.

Composability: How can your proposed developer tooling (existing or new) facilitate seamless interaction between different protocols and tools built on Arbitrum, the Nova ecosystem and other Orbit chains.

Scaffold Stylus will facilitate seamless interaction across Arbitrum, Nova, and other Orbit chains through several key design principles:

Unified Configuration Layer: Scaffold Stylus will implement a agnostic configuration system that allows developers to define connection parameters for multiple mainnet chains (Arbitrum One, Nova, Orbit chains) in a single configuration file. This enables applications to interact with multiple chains without code duplication.
Connector Library: We'll develop a connector library that abstracts away the specific details of interacting with different Arbitrum ecosystem chains. This will provide a consistent API for contract interactions regardless of whether they're deployed on Arbitrum One, Nova, or custom Orbit chains.
Network-Aware Component System: Our React component library will include network-aware components that can automatically adapt to the current chain context. For example, a transaction component that can route to the appropriate chain based on the transaction type and target.
Deployment Pipeline: The deployment pipeline will support simultaneous or sequential deployment to multiple Arbitrum ecosystem chains, allowing developers to maintain consistent application versions across environments.
Chain Detection and Switching: The framework will include utilities for detecting the current chain and prompting users to switch chains when necessary for specific functionality, creating a smooth user experience across the ecosystem.
Shared Type System: The type-safe binding system will support contract interfaces deployed across different chains, allowing developers to maintain type safety even when interacting with contracts on multiple networks.
Adoption: If your grant focuses on a Growth or Orbit Chain developer tool, how would you ensure its widespread adoption within the developer community.

Focus more on Growth

1.Low-Friction Onboarding

One-command setup via npx create-stylus@latest
Interactive tutorials that guide developers through first deployment in under 15 minutes
Pre-configured templates for common application patterns: Defi, NFTs, Gaming.
2.Educational Content Strategy

Regular workshop series targeting both Solidity developers and Rust/C++ developers new to blockchain
Comprehensive documentation with visual guides and interactive examples
Collaboration with Arbitrum's education initiatives
3.Community Building

Dedicated Telegram group for real-time support and knowledge sharing
Exclusive support during Arbitrum Hackathons for teams that use scaffold stylus
4.Strategic Partnerships

Collaborate with key projects in the Arbitrum ecosystem to showcase integration
Partner with developer bootcamps to include Scaffold Stylus in curriculum
5.Showcase Applications

Build and promote reference applications that demonstrate Stylus capabilities
Highlight community success stories and case studies
Maintain a public directory of applications built with Scaffold Stylus
6.Developer Experience Focus

Continuously gather and incorporate user feedback
Regular releases with meaningful improvements
Comprehensive GitHub issue management
7.Growth Metrics Tracking

Monitor adoption metrics (downloads, stars, forks)
Track developer satisfaction through surveys
Identify and address friction points in the developer journey
If working on Orbit Chain Onboarding and Tooling: How would you adapt your existing developer tooling (or propose a new tool) to simplify building applications on custom Arbitrum Layer 3 chains (Orbit Chains).

While our primary focus is Stylus development on Arbitrum One, Scaffold Stylus will still support Orbit chain deployments through:

Flexible Chain Configuration A simple configuration system that works across Arbitrum One and Orbit chains, allowing developers to deploy to either environment with minimal changes.
Network-Agnostic Components React components and hooks that automatically adapt to the current network context, whether Arbitrum One or an Orbit chain.
Deployment Pipeline Supporting deployments to both Arbitrum One and Orbit chains through the same streamlined workflow.
Chain Detection Utilities Helpers for detecting and prompting chain switching when needed for cross-chain applications.
Instagram.

na

If applying for a growth oriented grant: Please provide success metrics for the grant with milestone-oriented disbursements.

Success Metrics by Milestone
Milestone 1: Core Architecture

10+ GitHub stars within 4 weeks
Nitro node startup <2 minutes
Type-safe binding for 4+ contract patterns
80%+ UI/UX approval rating

Milestone 2: Development Experience

Hot reload <3 seconds latency
10+ Stylus-specific components
85%+ test coverage
10+ external beta testers
<2 minute sepolia testnet and arbitrum one mainnet deployment

Milestone 3: Templates & Documentation
100% core documentation coverage

CLI project creation <30 seconds
base template + 4 templates extension
100%+ documentation coverage
30+ developers onboarded
20+ GitHub stars in third month
3+ community applications built
<2 minute arbitrum one nova and orbit chain deployment

LinkedIn.

https://www.linkedin.com/in/gianalarcon/

Discord.

@gianalarcon

Others.

https://github.com/gianalarcon

Do you acknowledge that your team will be subject to a KYC requirement.

Yes

Do you acknowledge that, in case of approval, you will have to provide a report at the completion of the grant and, three months later, complete a survey about your experience.

Yes

Team experience and completeness.

Gian Alarcon (Project Lead): Software Engineer with degree in Systems Engineering (UNMSM, Peru) and Intelligence Science Technology (USTB, China). Main contributor to Scaffold-Stark and Director at Quantum3Labs. Brings essential experience in building developer frameworks for novel blockchain environments. Proficiency in Rust backend development, particularly valuable for Stylus' Rust-based smart contracts. Additional contributions to the Starknet Dojo framework and Onchain game The Marquis

Richard Sulisthio: Computer Science graduate from Tsinghua University with 3+ years specialized blockchain framework development. Contributor to Scaffold-ETH and maintainer of Scaffold-Stark, brings crucial continuity between these previous frameworks and Scaffold Stylus. Expertise in React/TypeScript ensures our frontend components and hooks will integrate seamlessly with Stylus contracts.

Bao Ho Gia: Full-stack developer and DevOps specialist with cross-chain experience across Ethereum, Starknet, Sui, and Solana ecosystems. Bao will lead blockchain integration, support on creation of components and hooks, and implementation of DevOps infrastructure
