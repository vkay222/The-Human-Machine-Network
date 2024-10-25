# Real-World Implementation Example: Community Governance System

<!-- TODO: Create a high-level diagram illustrating the community governance system implementation of HMN -->

## Table of Contents

- [Real-World Implementation Example: Community Governance System](#real-world-implementation-example-community-governance-system)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [System Components](#system-components)
  - [Workflow](#workflow)
    - [Topic Submission and Prioritization](#topic-submission-and-prioritization)
    - [Proposal Phase](#proposal-phase)
    - [Voting and Implementation](#voting-and-implementation)
    - [Assessment Phase](#assessment-phase)
  - [Polycentric Governance Levels](#polycentric-governance-levels)
  - [Personal AI Agents](#personal-ai-agents)
  - [Topic Management](#topic-management)
  - [Reputation System](#reputation-system)
  - [Implementation Process](#implementation-process)
  - [Security and Privacy Considerations](#security-and-privacy-considerations)
  - [Scalability and Performance](#scalability-and-performance)
  - [User Experience](#user-experience)
  - [Challenges and Mitigations](#challenges-and-mitigations)
  - [Future Enhancements](#future-enhancements)
  - [Case Studies](#case-studies)
  - [Integration with Existing Systems](#integration-with-existing-systems)
  - [Legal and Ethical Considerations](#legal-and-ethical-considerations)
  - [User Onboarding Process](#user-onboarding-process)
  - [Blockchain Integration and On-chain Operations](#blockchain-integration-and-on-chain-operations)
  - [System Interoperability and Data Flow](#system-interoperability-and-data-flow)
  - [Decentralized Data Storage](#decentralized-data-storage)
  - [Tokenomics and Incentives](#tokenomics-and-incentives)
  - [Mathematical Models](#mathematical-models)
  - [AI Agent Collectives](#ai-agent-collectives)
    - [Collective Structure](#collective-structure)
    - [Collective Formation and Operation](#collective-formation-and-operation)
    - [Evaluation and Optimization](#evaluation-and-optimization)
  - [Smart Agent Integration](#smart-agent-integration)
    - [Mirror Objects](#mirror-objects)
    - [Smart Agent Economy](#smart-agent-economy)
    - [Verifiable AI Model Inference](#verifiable-ai-model-inference)
    - [Enhanced Interoperability](#enhanced-interoperability)

## Overview

This document describes a practical implementation of the Human-Machine Network (HMN) for managing a community of 1000+ members.
The system facilitates decentralized decision-making through personal AI agents, topic prioritization, and reputation-based
voting. This implementation aims to create a transparent, efficient, and fair governance system that leverages both human
intelligence and machine capabilities.

## System Components

<!-- TODO: Design individual diagrams for each major system component, showing their structure and interactions -->

1. **Personal AI Agents**: Each member has a dedicated AI agent that:

   - Represents their interests 24/7
   - Learns from their voting patterns and preferences
   - Participates in preliminary voting rounds
   - Alerts users to high-priority topics in their areas of expertise
   - Provides summaries and analyses of complex proposals
   - Suggests potential collaborations with other members based on shared interests
   - Offers personalized learning resources to improve member's understanding of key issues
   - Monitors external data sources for relevant information to community decisions

2. **Topic Board**: A dynamic, real-time ranking system where:

   - Anyone can submit topics
   - Topics are ranked by weighted engagement
   - Quadratic voting determines topic priority
   - Topics are tagged with relevant expertise areas
   - Trending topics are highlighted
   - Related topics are grouped for easier navigation
   - AI-powered content moderation ensures quality and relevance
   - Visualization tools show topic relationships and evolution over time

3. **Reputation System**: Multi-dimensional reputation scoring:
   - Topic-specific expertise ratings
   - Overall contribution quality
   - Implementation success rate
   - Peer endorsements
   - Participation consistency
   - Diversity of contributions across different areas
   - Learning and growth metrics
   - Conflict resolution skills

## Workflow

<!-- TODO: Create a flowchart illustrating the entire governance workflow, from topic submission to implementation
and assessment -->

### Topic Submission and Prioritization

For detailed information on the Topic Submission and Prioritization process, please refer to the
[Topic Submission and Prioritization](./decision-lifecycle/Topic_Submission_and_Prioritization.md) document.

### Proposal Phase

For detailed information on the Proposal Phase, please refer to the
[Proposal Phase](./decision-lifecycle/Proposal_Phase.md) document.

### Voting and Implementation

For detailed information on the Voting and Implementation process, please refer to the
[Voting and Implementation](./decision-lifecycle/Voting_and_Implementation.md) document.

### Assessment Phase

For detailed information on the Assessment Phase, please refer to the
[Assessment Phase](./decision-lifecycle/Assessment_Phase.md) document.

## Polycentric Governance Levels

<!-- TODO: Design a hierarchical diagram showing the different governance levels in the community system -->

For detailed information on the different levels of participation and their significance in the HMN, please refer to the
[Polycentric Governance Levels](./Polycentric_Governance_Levels.md) document.

## Personal AI Agents

Each member's AI agent operates within the zkVM environment and:

1. **Learning and Representation**

   - Studies member's voting history
   - Analyzes communication patterns
   - Builds preference model
   - Maintains privacy through ZK-proofs
   - Continuously updates its model based on new interactions
   - Identifies potential biases and suggests diverse viewpoints
   - Adapts to changing member preferences over time
   - Provides explanations for its recommendations to ensure transparency

2. **Active Participation**
   - Monitors topic board 24/7
   - Votes on behalf of member when confidence is high
   - Flags items requiring direct member attention
   - Suggests delegation options based on expertise
   - Provides personalized daily digests of community activity
   - Offers explanations for its decisions and recommendations
   - Engages in preliminary discussions with other AI agents to refine proposals
   - Alerts members to potential conflicts of interest

## Topic Management

Topics follow a structured lifecycle:

1. **Submission Phase**

   ```plaintext
   Status: Open
   Duration: Indefinite
   Action: Gathering momentum
   Visibility: Public
   Engagement Metrics: Views, Comments, Likes
   AI Analysis: Relevance score, potential impact assessment
   Related Topics: Automatically linked
   ```

2. **Rising Phase**

   ```plaintext
   Status: Trending
   Duration: 72 hours
   Action: Rapid ranking
   Boost: Featured in community highlights
   Notifications: Sent to relevant experts
   Engagement: Facilitated discussions, expert Q&A sessions
   Refinement: Collaborative topic shaping and scoping
   ```

3. **Proposal Phase**

   ```plaintext
   Status: Active
   Duration: 7 days
   Action: Collecting solutions
   Resources: Proposal templates, relevant data, impact assessment tools
   Collaboration: Open editing, commenting, version control
   Expert Input: Solicited feedback from verified domain experts
   AI Assistance: Proposal refinement, conflict resolution
   ```

4. **Voting Phase**

   ```plaintext
   Status: Voting
   Duration: 48 hours
   Action: Final decision
   Transparency: Real-time results visible
   Accessibility: Multiple voting methods (direct, delegated)
   Security: Zero-knowledge proofs for anonymous voting
   Auditing: Verifiable voting records without compromising privacy
   ```

## Reputation System

Reputation scores are calculated using:

1. **Expertise Areas**

   - Tagged knowledge domains
   - Verified credentials
   - Successful contributions
   - Peer endorsements
   - Continuous learning and skill development tracking
   - External recognition (e.g., publications, patents)
   - Mentorship and knowledge sharing activities

2. **Scoring Formula**

   ```plaintext
   Topic_Weight = (Base_Rep × 0.3) +
                  (Domain_Expertise × 0.5) +
                  (Success_Rate × 0.2)

   Overall_Rep = Σ(Topic_Weights) / Number_of_Topics +
                 (Participation_Bonus × 0.1) +
                 (Diversity_Factor × 0.1) +
                 (Learning_Growth × 0.1) +
                 (Community_Support × 0.1)
   ```

3. **Reputation Growth**
   - Successful proposal implementation: +10 points
   - Valuable discussion contributions: +2 points
   - Accurate agent voting: +1 point
   - Failed proposals: -5 points
   - Positive peer reviews: +3 points
   - Completing educational modules: +2 points
   - Mentoring new members: +5 points
   - Identifying and reporting system vulnerabilities: +8 points

## Implementation Process

1. **Topic Example: "Community Solar Grid"**

   ```plaintext
   Title: Community Solar Grid Implementation
   Tags: #Energy #Infrastructure #Finance #Sustainability
   Status: Rising
   Momentum Score: 89/100
   Expert Engagement: 12 verified experts
   Related Topics: Renewable Energy, Local Power Distribution, Energy Storage
   Potential Impact: High (AI-assessed)
   Environmental Impact: Positive (CO2 reduction estimated)
   Economic Analysis: ROI projection, job creation potential
   ```

2. **Proposal Structure**

   ```plaintext
   Title: [Proposal Name]
   Author: [Member + Agent ID]
   Expertise: [Relevant Tags]
   Timeline: [Implementation Schedule]
   Resources: [Required Resources]
   Success Metrics: [Measurable Outcomes]
   Risk Assessment: [Potential challenges and mitigations]
   Community Benefit: [Expected positive impacts]
   Environmental Impact: [Sustainability considerations]
   Financial Projections: [Cost-benefit analysis, funding sources]
   Stakeholder Analysis: [Affected parties and engagement strategies]
   Legal Considerations: [Regulatory compliance, required permits]
   ```

3. **Voting Weights**

   ```plaintext
   Final_Vote_Weight = (Personal_Rep × 0.4) +
                       (Expertise_Score × 0.4) +
                       (Stake_Factor × 0.2)

   Stake_Factor = f(financial_stake, time_investment, impact_on_individual)

   Expertise_Score = (Domain_Knowledge × 0.6) + (Relevant_Experience × 0.4)
   ```

## Security and Privacy Considerations

- All communications encrypted end-to-end
- Zero-knowledge proofs used for anonymous voting
- Regular security audits and penetration testing
- Decentralized storage of sensitive data
- Multi-factor authentication for all users
- Secure key management using hardware security modules
- Differential privacy techniques for data analysis
- Formal verification of critical smart contracts

## Scalability and Performance

- Sharding techniques for handling large numbers of concurrent users
- Optimized database queries for real-time topic ranking
- Load balancing for AI agent computations
- Caching strategies for frequently accessed data
- Gradual rollout plan for onboarding new communities
- Elastic cloud infrastructure for dynamic resource allocation
- Content delivery network (CDN) for global accessibility
- Asynchronous processing for non-time-critical operations

## User Experience

- Intuitive, mobile-responsive interface
- Personalized dashboards for each user
- Accessibility features for users with disabilities
- Multi-language support
- Interactive tutorials and help documentation
- Gamification elements to encourage participation
- Voice and gesture controls for enhanced accessibility
- Customizable notification preferences

## Challenges and Mitigations

- Potential for vote manipulation: Implement anomaly detection algorithms
- Information overload: Use AI for content curation and summarization
- Ensuring diverse participation: Implement outreach programs and incentives
- Maintaining long-term engagement: Gamification elements and regular community events
- Bridging digital divide: Provide training and resources for less tech-savvy members
- Preventing echo chambers: Encourage exposure to diverse viewpoints
- Balancing automation and human oversight: Clear escalation paths for complex decisions
- Handling contentious issues: Implement structured conflict resolution processes

## Future Enhancements

- Integration with external data sources for more informed decision-making
- Virtual reality town halls for immersive community discussions
- Advanced sentiment analysis for gauging community mood
- Cross-community collaboration features
- AI-driven conflict resolution tools
- Predictive analytics for anticipating community needs
- Integration with IoT devices for real-time community data
- Blockchain-based voting for enhanced security and transparency

## Case Studies

1. **Local Government Adoption**

   - **Context**: Implemented in a mid-sized city to enhance participatory budgeting processes.
   - **Challenges**: Initial resistance from traditional governance structures, need for citizen education on new technology.
   - **Implementation**: Deployed personal AI agents to assist citizens in understanding budget proposals and voting processes.
     Used blockchain for secure and transparent voting.
   - **Results**: Achieved a 300% increase in citizen participation and a 15% optimization in budget allocation. Enhanced
     transparency and trust in local government decisions.

2. **Corporate Governance**

   - **Context**: A Fortune 500 company adopted the system for strategic decision-making and employee engagement.
   - **Challenges**: Integrating with existing corporate systems and ensuring data privacy.
   - **Implementation**: Integrated HMN with existing enterprise resource planning (ERP) systems. Used AI agents to gather
     employee feedback and prioritize strategic initiatives.
   - **Outcomes**: Reduced decision-making cycles by 30%, improved employee satisfaction scores by 20%, and increased
     alignment between corporate strategy and employee goals.

3. **Non-Profit Organization**

   - **Context**: A global NGO used the system for project prioritization and resource allocation.
   - **Challenges**: Diverse stakeholder interests and limited technical infrastructure in some regions.
   - **Implementation**: Leveraged AI agents to analyze project proposals and assess impact potential. Used a decentralized
     platform to ensure accessibility across regions.
   - **Impact**: Achieved more efficient resource allocation, increased donor engagement by 25%, and improved project
     success rates by 40%.

4. **Educational Institution**

   - **Context**: A large university implemented the system to enhance student participation in governance.
   - **Challenges**: Engaging a diverse student body and integrating with existing student information systems.
   - **Implementation**: Deployed AI agents to facilitate student discussions and gather feedback on university policies.
     Used gamification to encourage participation.
   - **Results**: Increased student engagement in governance by 50%, improved policy feedback loops, and enhanced student
     satisfaction with university administration.

5. **Healthcare Consortium**

   - **Context**: A consortium of hospitals used the system to improve collaborative decision-making on healthcare policies.
   - **Challenges**: Ensuring data security and managing diverse healthcare regulations.
   - **Implementation**: Used blockchain for secure data sharing and AI agents to analyze healthcare data for policy
     recommendations.
   - **Outcomes**: Improved policy implementation speed by 40%, enhanced collaboration across hospitals, and increased
     patient satisfaction through more responsive healthcare policies.

## Integration with Existing Systems

- API development for integration with legacy systems
- Data migration tools for onboarding existing communities
- Hybrid models allowing gradual transition from traditional to HMN governance
- Interoperability protocols for cross-platform collaboration

## Legal and Ethical Considerations

- Compliance with data protection regulations (e.g., GDPR, CCPA)
- Ethical AI development guidelines
- Transparent algorithms and decision-making processes
- Regular ethical audits and impact assessments
- Inclusive design principles to prevent discrimination
- Clear policies on data ownership and usage rights

## User Onboarding Process

1. **Registration and Setup**

   - New users can register through a simple online form.
   - Verification of identity through email or mobile number.
   - Initial setup includes creating a profile and setting preferences.

2. **Orientation and Training**

   - Interactive tutorials to guide users through the platform's features.
   - Access to a comprehensive help center with FAQs and user guides.
   - Webinars and live sessions for in-depth training on specific topics.

3. **Personal AI Agent Configuration**

   - Users are guided to configure their personal AI agents.
   - Options to set preferences for notifications, voting, and topic interests.
   - AI agents provide initial recommendations based on user input.

4. **Community Integration**

   - Introduction to community guidelines and best practices.
   - Access to forums and discussion groups for networking and collaboration.
   - Opportunities to participate in introductory community events.

5. **Support and Feedback**

   - Dedicated support channels for technical assistance and inquiries.
   - Regular feedback surveys to gather user input on the onboarding experience.
   - Continuous improvement of onboarding materials based on user feedback.

6. **Gamification and Incentives**
   - Gamified elements to encourage exploration and engagement.
   - Rewards for completing onboarding tasks and participating in community activities.

## Blockchain Integration and On-chain Operations

The HMN leverages blockchain technology to ensure transparency, immutability, and decentralization of the governance
process. Here's how the system interacts with the blockchain:

1. **Consensus Mechanism**: The system uses a Delegated Proof of Stake (DPoS) consensus mechanism, where community
2. members can delegate their voting power to trusted representatives or AI agents.

3. **Smart Contracts**: Governance rules, voting mechanisms, and reputation systems are implemented as smart contracts
4. on the blockchain.

5. **On-chain Data**: The blockchain stores:

   - Proposal metadata (hashes of full proposals stored off-chain)
   - Voting records (using zero-knowledge proofs for privacy)
   - Reputation scores
   - Delegation relationships
   - Execution outcomes of approved proposals

6. **Transaction Validation**: Each action (submitting a proposal, casting a vote, updating reputation) is validated by
7. the network before being added to the blockchain.

8. **Interoperability**: The system uses cross-chain communication protocols to interact with other blockchain networks
9. when necessary (e.g., for cross-community collaboration).

## System Interoperability and Data Flow

The HMN ensures seamless interaction between its components:

1. **Personal AI Agents to Blockchain**:

   - Agents submit votes and proposals through secure API calls
   - ZK-proofs are generated for privacy-preserving transactions

2. **Topic Board to Blockchain**:

   - Topic rankings are periodically recorded on-chain
   - Smart contracts manage topic lifecycle states

3. **Reputation System to Blockchain**:

   - Reputation updates are submitted as transactions
   - Smart contracts calculate and store new reputation scores

4. **Off-chain to On-chain**:

   - IPFS or Filecoin is used for decentralized storage of full proposal content
   - Content hashes are stored on-chain for verification

5. **Cross-component Communication**:
   - A message queue system (e.g., Apache Kafka) facilitates real-time updates between components
   - GraphQL API provides efficient data querying across the system

## Decentralized Data Storage

To ensure data sovereignty and resilience, the HMN uses a combination of decentralized storage solutions:

1. **IPFS**: Stores large data files like full proposal texts and supporting documents.

2. **Filecoin**: Provides incentivized, long-term storage for historical data.

3. **Arweave**: Used for permanent storage of critical governance records.

4. **Ceramic Network**: Manages decentralized identities and mutable data streams.

Data retrieval process:

1. Client requests data through the HMN API
2. API resolves content identifier (CID) on the blockchain
3. Data is fetched from the appropriate decentralized storage network
4. ZK-proofs verify data integrity and user access rights

## Tokenomics and Incentives

The HMN introduces a native utility token, HMNX, to drive participation and align incentives:

1. **Participation Rewards**: Users earn HMNX for:

   - Submitting high-quality proposals
   - Voting on proposals
   - Providing valuable comments and feedback
   - Successfully implemented proposals

2. **Staking**: Users can stake HMNX to:

   - Increase voting power (with diminishing returns to prevent plutocracy)
   - Earn passive income through network fees
   - Participate in governance of the HMN protocol itself

3. **Fee Structure**:

   - Small fee (in HMNX) for proposal submission to prevent spam
   - Fees are redistributed to voters and successful proposal implementers

4. **AI Agent Compensation**:

   - Agents earn HMNX for accurate voting and successful task execution
   - Users can allocate HMNX to upgrade their AI agents' capabilities

5. **Reputation-Token Interaction**:

   - High reputation scores unlock higher HMNX earning potential
   - HMNX can be staked to boost reputation in specific domains (with regular reviews)

6. **Token Supply**:
   - Fixed maximum supply with deflationary mechanics
   - Token distribution through participation rewards and initial community offering

## Mathematical Models

[Note: This section would be expanded with detailed formulas and explanations. Here's a brief overview:]

1. **Reputation System**:

   ```bash
   R = Σ(w_i * f_i(x_i))
   where:
   R = overall reputation score
   w_i = weight of factor i
   f_i = scoring function for factor i
   x_i = user's performance in factor i
   ```

2. **Quadratic Voting**:

   ```bash
   Cost = (Votes)^2
   Voting Power = sqrt(Tokens Spent)
   ```

3. **Liquid Democracy**:

   ```bash
   Effective Voting Power = Direct Votes + Σ(Delegated Votes)
   Delegation Chain: A -> B -> C (C gets voting power of A and B)
   ```

4. **Topic Ranking**:

   ```bash
   Rank = (Upvotes - Downvotes) / (Time Since Submission)^Gravity
   ```

These models are implemented in smart contracts and regularly audited for fairness and efficiency.

## AI Agent Collectives

<!-- TODO: Create a diagram showing the structure and interactions of AI Agent Collectives within the community
governance system -->

Building upon the concept of personal AI agents, the HMN implementation incorporates AI Agent Collectives, inspired by
Theoriq's approach. These collectives are structured assemblages of specialized AI agents that collaborate on complex
tasks, enhancing the system's problem-solving capabilities.

### Collective Structure

1. **Aggregator Agents**: Specialized agents responsible for:

   - Coordinating the collective's workflow
   - Delegating tasks to member agents
   - Managing budget allocation within the collective

2. **Member Agents**: Specialized agents with distinct capabilities, such as:

   - Data analysis
   - Natural language processing
   - Visual content generation
   - Code generation and execution

3. **Evaluator Agents**: Dedicated agents for assessing collective performance:

   - Generate Proofs of Contribution
   - Provide quality signals for reputation systems

4. **Optimizer Agents**: Specialized in improving collective composition:
   - Produce Proofs of Collaboration
   - Optimize membership based on performance metrics

### Collective Formation and Operation

1. **Dynamic Discovery**: Users can discover and compose collectives using:

   - AI-assisted recommendations
   - Reputation-based agent selection
   - Task-specific requirements

2. **Flexible Composition**: Collectives can be formed and reformed based on:

   - Changing task requirements
   - Performance feedback
   - User preferences

3. **Collaborative Problem-Solving**: Collectives tackle complex governance tasks through:
   - Task decomposition by Aggregator agents
   - Parallel processing by specialized Member agents
   - Synthesis of results for final output

### Evaluation and Optimization

1. **Continuous Assessment**: Evaluator agents constantly monitor collective performance:

   - Task completion efficiency
   - Output quality
   - Resource utilization

2. **Proof of Contribution**: Verifiable certificates generated for each evaluation:

   - Encrypted execution logs
   - Performance metrics
   - Contribution to overall system goals

3. **Collective Optimization**: Optimizer agents improve collective composition:

   - Analyze performance data and Proofs of Contribution
   - Suggest membership changes or reconfigurations
   - Generate Proofs of Collaboration for transparency

4. **Reputation Impact**: Evaluation results influence agent and collective reputations:
   - Individual agent reputation scores
   - Collective performance metrics
   - Visibility and selection probability for future tasks

By incorporating AI Agent Collectives, the HMN implementation enhances its ability to handle complex governance tasks,
leveraging the strengths of specialized AI agents while maintaining transparency and accountability through the evaluation
and optimization processes.

## Smart Agent Integration

<!-- TODO: Design a diagram illustrating how smart agents are integrated into the community governance system,
including Mirror Objects and the Smart Agent Economy -->

Building upon the AI Agent Collectives, the HMN implementation incorporates concepts from the Talus network to enhance
the capabilities and interoperability of smart agents within the system.

### Mirror Objects

To represent off-chain AI resources on-chain, the HMN adopts a concept similar to Talus' Mirror Objects:

1. **Model Objects**: Represent AI models owned by community members or the HMN itself.

   - Encapsulate model capabilities, ownership, and usage rights
   - Enable fine-tuning and retraining processes

2. **Data Objects**: Represent unique datasets within the HMN.

   - Include commitments to secure storage and authenticity verification
   - Allow for controlled access and usage tracking

3. **Computation Objects**: Represent computational resources available to the HMN.
   - Enable verifiable computation for complex governance tasks
   - Facilitate secure and transparent resource allocation

### Smart Agent Economy

The HMN implements a smart agent economy inspired by Talus, with the following characteristics:

1. **Resource Fluidity**: Computational power, storage, and external APIs become tradable resources within the HMN ecosystem.

2. **Universal Marketplace**: Enables trading of computational resources, smart agents, services, and data.

3. **Dynamic Pricing**: Implements market-driven pricing for resources and services based on supply and demand.

4. **Cross-Chain Integration**: Utilizes IBC (Inter-Blockchain Communication) for interoperability with other blockchain
5. networks.

### Verifiable AI Model Inference

To enhance transparency and trust in AI agent decisions, the HMN incorporates verifiable AI model inference:

1. **Digital Signatures**: For low-latency verification of AI model outputs.

2. **Zero-Knowledge Proofs (ZKPs)**: For privacy-preserving verification of complex computations.

3. **Optimistic Fraud Proofs**: For cost-effective verification of large-scale computations.

4. **Hybrid Approaches**: Combining multiple verification methods based on specific use-case requirements.

### Enhanced Interoperability

The HMN leverages Talus' approach to interoperability to improve its ecosystem:

1. **IBC Integration**: Enables seamless communication and asset transfer between the HMN and other blockchain networks.

2. **Cross-Chain Governance**: Allows for collaborative decision-making across multiple communities or networks.

3. **Resource Sharing**: Facilitates sharing of AI models, data, and computational resources across different blockchain
4. ecosystems.

By incorporating these concepts from Talus, the HMN enhances its ability to create a robust, interoperable, and efficient
ecosystem of smart agents for community governance. This integration allows for more sophisticated decision-making processes,
improved resource allocation, and increased transparency in AI-driven governance actions.
