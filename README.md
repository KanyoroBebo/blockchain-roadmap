# ✅ Blockchain Smart Contract + Security Roadmap

**Schedule:** ~27 hours/week (5h weekdays + 2h Saturday)  
**Goal:** Become a Smart Contract Developer with a strong focus on Security & Auditing.

---

## 📘 Phase 1: Blockchain & Solidity Foundations (Weeks 1–4)
**Objective:** Understand how blockchain and Solidity work; deploy simple contracts.

<details>
<summary>🗓️ Week 1 – Blockchain Basics</summary>

- [x] Learn what a blockchain is (blocks, nodes, consensus)
- [x] Study Ethereum architecture (EVM, gas, accounts)
- [x] Watch “Intro to Ethereum” (freeCodeCamp or Dapp University)
- [x] Read: [ethereum.org → What is Ethereum?](https://ethereum.org/en/what-is-ethereum/)
- [x] Install MetaMask and explore test networks (Sepolia/Goerli)

</details>

<details>
<summary>🗓️ Week 2 – Solidity Syntax</summary>

- [x] Complete **CryptoZombies** up to level 5  
- [ ] *Study **[Solidity by Example](https://solidity-by-example.org)** (High priority, review this site repeatedly)* - [x] Understand visibility, modifiers, and constructors  
- [x] Deploy a simple contract in Remix IDE  

</details>

<details>
<summary>🗓️ Week 3 – Data Structures & Inheritance</summary>

- [x] Learn arrays, mappings, structs  
- [x] Practice modifiers, events, and error handling  
- [x] Learn inheritance and interfaces  

</details>

<details>
<summary>🗓️ Week 4 – 🧩 Project #1: MyToken (ERC-20)</summary>

- [x] Implement ERC-20 token (mint, burn, transfer)
- [x] Test in Remix with multiple accounts
- [ ] *Re-implement by inheriting from **OpenZeppelin Contracts** (standard, secure method)*
- [x] Write README.md explaining token logic
- [x] Push to GitHub ✅  

</details>

---

## ⚙️ Phase 2: Tooling & Workflow (Weeks 5–9)
**Objective:** Move from Remix to a full professional dev setup using Foundry.

<details>
<summary>🗓️ Week 5 – Environment Setup</summary>

- [x] Install Foundry (`forge`, `cast`, `anvil`)  
- [x] Initialize a new Foundry project  
- [x] Learn compilation, deployment, and testing commands  

</details>

<details>
<summary>🗓️ Week 6 – Foundry Testing & Scripts</summary>

- [x] Write unit tests in Solidity using `forge-std/Test.sol`  
- [x] Create and run deployment scripts  
- [x] Simulate contract interactions on Anvil (local blockchain)  

</details>

<details>
<summary>🗓️ Week 7 – Integrating Front-End</summary>

- [ ] Set up React + Ethers.js  
- [ ] Connect MetaMask wallet and display account info  
- [ ] Build basic UI to interact with contract  
- [ ] *Note: Useful skill, but optional if focusing purely on security. Don't let it block Phase 3.*

</details>

<details>
<summary>🗓️ Week 8–9 – 🧩 Project #2: Decentralized Crowdfunding dApp</summary>

- [ ] Smart contract: campaign creation, funding, withdrawal  
- [ ] Front-end: campaign dashboard with wallet connect  
- [ ] Tests: ensure proper fund transfers  
- [ ] Document & push to GitHub ✅  

</details>

---

## 🔐 Phase 3: Smart Contract Security Fundamentals (Weeks 10–13)
**Objective:** Learn common vulnerabilities and how to secure contracts.

<details>
<summary>🗓️ Week 10 – Vulnerabilities Overview</summary>

- [ ] Study reentrancy, tx.origin misuse, overflow/underflow  
- [ ] *Study common **Access Control** issues (onlyOwner, insecure roles)*
- [ ] Review **[SWC Registry](https://swcregistry.io)** - [ ] Read OpenZeppelin’s security best practices  

</details>

<details>
<summary>🗓️ Week 11 – Capture The Flags</summary>

- [ ] Complete first 5 **[Ethernaut](https://ethernaut.openzeppelin.com)** levels  
- [ ] Solve 2–3 **[Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz)** challenges  
- [ ] *Note: DVD is advanced. It's okay if this is challenging; the goal is to learn, not just to solve.*
- [ ] Read one real audit report (Code4rena or OpenZeppelin)  

</details>

<details>
<summary>🗓️ Week 12–13 – 🧩 Project #3: Vulnerable Vault</summary>

- [ ] Create a Vault contract with a reentrancy bug  
- [ ] Write exploit contract to drain ETH  
- [ ] Patch vulnerability and re-test  
- [ ] Write `audit.md` describing issue + mitigation  
- [ ] Push to GitHub ✅  

</details>

---

## 🧰 Phase 4: DeFi & Advanced Security Testing (Weeks 14–20)
**Objective:** Build DeFi-level protocols and perform fuzz testing + audits.

<details>
<summary>🗓️ Week 14–15 – Advanced Solidity & DeFi Concepts</summary>

- [ ] Study ERC-4626 vault standard  
- [ ] Learn about lending pools, oracles, AMMs  
- [ ] Explore flash loans and liquidation mechanics  

</details>

<details>
<summary>🗓️ Week 16–17 – Foundry Fuzzing & Invariant Testing</summary>

- [ ] Use Foundry Forge for property-based tests  
- [ ] Implement invariants for lending logic  
- [ ] Integrate static analysis with **Slither** </details>

<details>
<summary>🗓️ Week 18–20 – 🧩 Project #4: Mini DeFi Protocol</summary>

- [ ] Build a simple lending/borrowing contract  
- [ ] Implement collateral, interest, liquidation  
- [ ] Test using fuzzing + invariants  
- [ ] Write professional-style `audit-report.md`  
- [ ] Push to GitHub ✅  

</details>

---

## 🌐 Phase 5: Real-World Auditing & Visibility (Weeks 21–26)
**Objective:** Participate in real contests and build your audit portfolio.

<details>
<summary>🗓️ Week 21–22 – Audit Contests</summary>

- [ ] Join **Code4rena** or **Sherlock** contest  
- [ ] Submit one or more findings  
- [ ] Review **Immunefi** bounties  

</details>

<details>
<summary>🗓️ Week 23–24 – Independent Audit</summary>

- [ ] Pick open-source contract repo  
- [ ] Perform manual audit (access control, logic flaws)  
- [ ] Write audit report (title, severity, fix)  

</details>

<details>
<summary>🗓️ Week 25–26 – 🧩 Project #5: Audit Portfolio</summary>

- [ ] Create `web3-security-portfolio` GitHub repo  
- [ ] Add 3–5 audit reports (Vault, DeFi, external projects)  
- [ ] Include tools list + lessons learned in README  
- [ ] Share on LinkedIn/X for visibility ✅  

</details>

---

## 🎯 Phase 6: Specialization & Long-Term Goals
**Objective:** Continue developing expertise & portfolio presence.

- [ ] Learn **Rust** for Solana/Substrate  
- [ ] Study formal verification (Certora, Scribble)  
- [ ] Participate regularly in Code4rena contests  
- [ ] Write technical blog posts or tutorials  
- [ ] Apply for Web3 developer or security internships  

---

## 🗂️ Optional Bonus Projects
- [ ] “Secure Solidity Patterns” repository  
- [ ] “Recreated Smart Contract Hacks” repo (DAO, Parity Wallet, etc.)  
- [ ] “DeFi Security Handbook” — your notes + examples  
- [ ] “Audit Report Template” Markdown for future use  

---

## ⚡ Progress Tracking
Example format for tracking progress:
```markdown
### Phase 2: Hardhat Workflow
- [x] Installed Hardhat and created project
- [x] Wrote deployment scripts
- [ ] Built Crowdfunding dApp
