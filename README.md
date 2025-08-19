# Fantastic
🌐 Google Clarity Web3 Procurement Contract

A **Clarity smart contract** designed to demonstrate how procurement (bidding, evaluation, and awarding contracts) could be made transparent and auditable in **Web3** using the **Stacks blockchain**.  

This project simulates how an enterprise (like Google) might handle vendor procurement fairly — with bids, evaluations, and winner selection all logged immutably on-chain.

✨ Features

- **Create Procurement Projects**  
  Project owner can create new contract opportunities with metadata:  
  - title  
  - description hash (stored in IPFS/Arweave off-chain)  
  - deadline block height  

- **Vendor Bidding**  
  Vendors submit bids tied to their blockchain identity.  
  Each bid contains:  
  - cost (in STX or abstract units)  
  - proposal hash  

- **Evaluator Review**  
  Owner can assign evaluators who score proposals for quality and compliance.

- **Winner Selection**  
  Owner finalizes a winner **after the deadline**.  
  Winner is determined by a scoring + cost formula.

- **On-Chain Transparency**  
  All steps (project creation, bidding, scoring, and awarding) are logged via blockchain events.



