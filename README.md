# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

# NAME: KARTHIKEYAN D
# REG NO.: 212224230115

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

**Step 1: Problem Definition**
1.1 Define the task: Summarization of a 500-word technical article (“The Basics of Blockchain Technology”).
1.2 Identify evaluation parameters: Accuracy, Coherence, Simplicity, Speed, and User Experience.
1.3 Select AI platforms for evaluation: *ChatGPT, Gemini, Claude, Copilot* (or others available).

---

**Step 2: Input Preparation**
2.1 Collect the original technical article (\~500 words).
2.2 Preprocess text if needed (clean formatting, remove redundancies).
2.3 Standardize input so each platform receives the same text.

---

**Step 3: Prompting Strategy Design**
3.1 Define the four prompting techniques:

* **Zero-shot:** Directly ask for a summary without examples.
* **Few-shot:** Provide 1–2 examples of summaries, then request the output.
* **Chain-of-thought:** Ask the model to reason step by step before summarizing.
* **Role-based:** Instruct the model to take on a specific role (e.g., “Act as a teacher summarizing for undergraduates”).

3.2 Formulate uniform prompt templates for each technique.

---

**Step 4: Execution on AI Platforms**
4.1 Input the article and prompts into each platform.
4.2 Generate summaries using **all four prompting techniques** per platform.
4.3 Record output along with response time (speed).

---

**Step 5: Evaluation Metrics**
5.1 **Accuracy:** Compare key points of the summary with the original text.
5.2 **Coherence:** Check logical flow and readability.
5.3 **Simplicity:** Measure ease of understanding for undergraduates.
5.4 **Speed:** Note response time for output generation.
5.5 **User Experience:** Record ease of use, clarity, and satisfaction during interaction with the platform.

---

**Step 6: Comparative Analysis**
6.1 Create a results table (Platform × Prompting Technique × Evaluation Metric).
6.2 Assign scores (e.g., 1–5) for each metric.
6.3 Analyze which platform + prompting technique gives the best overall performance.

---

**Step 7: Conclusion**
7.1 Identify the most effective **prompting technique** across platforms.
7.2 Identify the most effective **AI platform** overall.
7.3 Provide recommendations for content curation teams.

---

## CHATGPT(GPT-5) - **OPENAI**:
### 1. Zero-shot Prompting:

Blockchain is a distributed ledger technology (DLT) that securely records and tracks transactions and assets across networks. It stores data in blocks linked together, ensuring immutability and transparency. Blockchain eliminates the need for centralized authorities, allowing direct peer-to-peer interactions. First proposed in 1991 and popularized by Bitcoin in 2009, it is now used in cryptocurrencies, decentralized finance (DeFi), NFTs, and smart contracts.

Key features include decentralization, where nodes maintain the system without a central body; immutability, ensuring data cannot be altered once verified; enhanced security through cryptographic hashing; distributed ledgers, where nodes verify and store transactions collectively; and consensus mechanisms, which ensure agreement among participants before adding new blocks.

Types of blockchain include:

Public blockchain: permissionless, open to all participants.

Private blockchain: permission-based, restricted to selected members.

Consortium blockchain: semi-decentralized, managed by multiple organizations.

Hybrid blockchain: combines public and private features, offering flexible access and confidentiality.

### 2. Few-shot Prompting:

Example: “Cloud computing allows remote data storage and services. It has features like scalability, cost-effectiveness, and flexibility. It can be public, private, or hybrid.”

Now summarizing Blockchain in the same way:
Blockchain is a digital ledger that records transactions securely using blocks. Its features include decentralization, immutability, transparency, and security. Blockchain ensures data integrity by requiring consensus from multiple nodes. Applications extend beyond cryptocurrency to finance, NFTs, and smart contracts. Types of blockchains are public, private, consortium, and hybrid, each differing in accessibility, control, and flexibility.

### 3. Chain-of-thought Prompting :

Blockchain is like a shared Google Doc but more secure and immutable.

Its key aim is decentralization, immutability, security, and consensus-driven validation.

Historically, it began in 1991 as research and became widely used with Bitcoin in 2009.

Features make it tamper-proof and transparent.

Four types exist: public (open), private (restricted), consortium (shared by multiple orgs), and hybrid (mix of public/private).

### 4. Role-based Prompting:

As your professor, let me simplify Blockchain for you:
Blockchain is a secure digital ledger where data is stored in connected blocks, making it immutable and tamper-proof. It works without a central authority, relying instead on nodes in a network that validate each transaction. Think of it like a shared Google Doc, but far more secure. Since its introduction with Bitcoin in 2009, blockchain has expanded into many areas such as finance, NFTs, and smart contracts. Its main features are decentralization, immutability, enhanced security through cryptography, distributed ledgers that promote transparency, and consensus mechanisms ensuring fair validation. There are four main types: public (open to everyone), private (restricted access), consortium (controlled by multiple organizations), and hybrid (mix of public and private).

---

## PERPLEXITY (PRO):

### Zero-Shot Summary:
Blockchain is a **distributed ledger technology** that securely records transactions and tracks assets across business networks. It consists of blocks connected to one another, making tampering with data extremely difficult. Key features include decentralization, immutability, cryptographic security, distributed ledgers, and consensus algorithms for transaction validation. Types of blockchain include public, private, consortium, and hybrid, each with varying levels of access and control.

### Few-Shot Summary:
- Blockchain is a secure way to record and distribute digital information.
- It uses interconnected blocks, making records permanent and hard to alter.
- Features: decentralized structure, immutability, strong security, distributed ledgers, and consensus mechanisms.
- Types:
  - Public: Open to anyone, transparent.
  - Private: Restricted to certain members, used internally.
  - Consortium: Managed by multiple organizations.
  - Hybrid: Mix of public and private, with flexible data control.

### Chain-of-Thought Summary:
Blockchain started as a means to create secure, digital records and became widely popular through **Bitcoin** in 2009. Its immutable ledger means transactions, once added and validated by the network’s nodes, can’t be changed or deleted. Security is reinforced by cryptographic hashing, and consensus algorithms ensure trust among participants, even without a central authority. Varied blockchain types offer different levels of openness, privacy, and collaboration.

### Role-Based Summary:
"As an IT instructor, I explain Blockchain as a tamper-proof digital ledger system. Its decentralization means no single party controls the data. Blockchain’s immutable structure ensures data integrity, validated by consensus among network nodes. There are four major types—public (open), private (restricted), consortium (multi-organization), and hybrid (blending both)—making blockchain adaptable for several contexts, whether public-facing or enterprise-specific."

---

## COPILOT - MICROSOFT:

### 🧪 Zero-Shot Summary:

Without prior examples, here’s a direct summary: Blockchain is a secure, decentralized digital ledger system that records transactions in interconnected blocks. It ensures transparency, immutability, and enhanced security through cryptographic hashing and consensus mechanisms. Blockchain eliminates the need for central authorities, making it ideal for digital currencies and secure data sharing. It comes in four types—public, private, consortium, and hybrid—each serving different organizational needs.

### 🎯 Few-Shot Summary:

Just like Google Docs allows multiple users to view and edit a document simultaneously, blockchain distributes data across a network. However, unlike Google Docs, blockchain ensures that once data is entered, it cannot be changed. For example, in a public blockchain like Bitcoin, anyone can view and verify transactions. In contrast, private blockchains restrict access to selected participants, similar to a company’s internal database. Consortium blockchains allow multiple organizations to collaborate, while hybrid blockchains combine public transparency with private control.

### 🧠 Chain-of-Thought Summary:

Let’s break down the concept step by step. Blockchain is a form of Distributed Ledger Technology (DLT), designed to record transactions and track assets in a secure, decentralized manner. It functions as a digital ledger shared across a network of computers, where each transaction is stored in a block, and blocks are linked together in a chain. Once data is recorded, it cannot be altered—making blockchain immutable and tamper-proof.

The technology was first conceptualized in 1991 but gained prominence in 2009 with the launch of Bitcoin, the first cryptocurrency built on blockchain. Since then, it has expanded into various domains including decentralized finance (DeFi), non-fungible tokens (NFTs), and smart contracts.

### 👨‍🏫 Role-Based Summary:

Imagine I’m your tech mentor guiding you through this. Blockchain is like a digital notebook that everyone in a group can see, but no one can erase or rewrite once a page is filled. Each page is a block, and the notebook is the chain. This system is decentralized—no single person controls it. Instead, everyone in the group (called nodes) verifies new entries through a process called consensus. This makes it secure and trustworthy.

There are four types of blockchain:

- **Public**: Open to everyone, like Bitcoin.
- **Private**: Restricted to specific users, often used by companies.
- **Consortium**: Shared among multiple organizations.
- **Hybrid**: A mix of public and private, offering flexibility.

Key features include:

- **Decentralization**: No central authority.
- **Immutability**: Data cannot be changed once recorded.
- **Security**: Cryptographic hashing protects data.
- **Distributed Ledger**: Everyone has a copy of the data.
- **Consensus**: Agreement among nodes ensures validity.

Blockchain is revolutionizing how we store, share, and secure digital information. Whether it’s money, contracts, or records, blockchain makes it transparent and tamper-proof.

## Result
<img width="756" height="641" alt="image" src="https://github.com/user-attachments/assets/2a00f17a-847b-42a6-a0a9-5550dbc50e55" />
