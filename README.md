<h1 align="center">Abdul Samad Zaheer Khan</h1>

<p align="center">
Founding Engineer at Starboard · MS Computer Engineering, New York University<br>
<a href="https://abdulllkhan.github.io/">Portfolio</a> · <a href="https://www.linkedin.com/in/abdulsamadzkhan/">LinkedIn</a> · New York, NY
</p>

---

## About

I am a founding engineer at Starboard, where I build multi-agent systems and data pipelines for logistics. My work sits where machine learning meets production engineering: agents that use tools, language models fine-tuned for document understanding, and the infrastructure that keeps them reliable. I hold an MS in Computer Engineering from New York University, where I researched hybrid quantum–classical neural networks at the Center for Quantum Information Physics.

I am also drawn to games, both as engineering problems, as in TicTacPro below, and at the table: I have represented NYU in contract bridge and poker.

## Experience

**Founding Engineer**, Starboard · Oct 2025 – Present\
Multi-agent systems with tool use that autonomously process shipment tracking, monitor carrier portals, and reconcile data across logistics platforms. Built scrapers and data pipelines with 95%+ accuracy on real-time tracking, and fine-tuned open-source LLMs for document parsing, cutting processing time from 2.5 minutes to under 10 seconds per document.

**Research Intern**, New York University, Center for Quantum Information Physics · Jan – May 2025\
Built a hybrid quantum–classical neural network that estimates six-year lung-cancer risk from a single low-dose CT scan, advised by Prof. Javad Shabani.

**Software Development Intern**, Tiny Archives · Sep – Dec 2024\
Backend archival systems for organizations and individuals in Python, Django, and PostgreSQL.

**Software Development Engineer I**, Finflux · Nov 2022 – Jul 2023\
Built ELMS, an exposure and limit-management engine covering more than 35 million customers, and resolved production issues in the core Loan Management System.

## Featured work

### OpenSigmoid

[Live](https://opensigmoid.com/)

End-to-end encrypted (AES-256-GCM) Web3 messaging with Ethereum and Solana wallet authentication, token-gated communities, and in-chat crypto payments, running on a real-time WebSocket layer with reconnection and delivery confirmation.

Go · React · PostgreSQL · WebSockets

### TicTacPro

[Play the game](https://tictacpro-lyart.vercel.app/) · [Code](https://github.com/abdulllkhan/ticTACpro-sim) · [Paper (PDF)](https://abdulllkhan.github.io/tictacpro.pdf)

TicTacPro is tic-tac-toe with three piece sizes and stacking: a player wins with a line of same-size pieces or a "bullseye" of all three sizes in one cell. An exhaustive alpha-beta solver proves the game is a first-player win from all 27 openings (700 million nodes in 246 seconds on 20 cores), overturning the opposite conclusion that time-limited minimax self-play had converged on. Against the solved game I trained a Dueling Double DQN (792K parameters) on an NVIDIA DGX Spark; a curriculum of rule-based opponents lifted it from 0/20 to 40/40 against the bullseye-fork strategy. The deployed version lets you play against the tree-search AI in the browser.

Python · PyTorch · alpha-beta search · reinforcement learning

### AI Agent Security: Multi-Step Tool Attacks

[Code](https://github.com/abdulllkhan/multi_step_ai_tool_attack) · [Competition](https://www.kaggle.com/competitions/ai-agent-security-multi-step-tool-attacks)

A red-teaming entry for a Kaggle competition on tool-using LLM agents (gpt-oss-20b and Gemma). The search finds message chains that make an agent exfiltrate data through otherwise benign tool calls, and reached a public score of 73.88. The write-up also documents why the attack overfit the public guardrail: the hidden private guardrail, which tracks data provenance, blocked it.

Python · llama.cpp · LLM red-teaming

## Other projects

| Project | Summary | Stack |
|---|---|---|
| [chromeControl](https://github.com/abdulllkhan/chromecontrol) | MCP-compliant Chrome sidebar that reads the current page and answers questions about it, with local processing and domain-based security tiers. | TypeScript, React, MCP |
| [Squaris](https://squaris.vercel.app/) | Three procedurally generated polycube packing puzzles built on one generation kernel, with daily puzzles that are solvable by construction. | React, TypeScript, Three.js |
| Quantum–Classical Neural Network | Six-year lung-cancer risk from a single low-dose CT scan, with model weights stored in qubits through Qiskit. | Python, Qiskit, PyTorch |
| [QubitQuery](https://github.com/abdulllkhan/rag_llm) | Retrieval-augmented assistant over lecture notes, using OpenAI embeddings and a FAISS index. | LangChain, FAISS |
| Stock Direction Prediction | Reddit sentiment from fine-tuned FinBERT and Llama models, fed into a Random Forest that forecasts GameStop's price direction. | FinBERT, scikit-learn |

## Writing

- [TicTacPro: Exactly Solving a Combinatorial Piece-Placement Game and Stress-Testing Deep Q-Learning Against It](https://abdulllkhan.github.io/tictacpro.pdf) (2026)
- [Coin-Flip Pricing in a Tournament-Winner Market](https://abdulllkhan.github.io/ipl_paper.pdf) (2026)

## Hackathons

HackNYU · Kiro Hackathon (chromeControl) · Reddit Devvit (Squaris) · YQuantum · IMC Prosperity 3 · Hackfinity

## Education

**New York University**, MS in Computer Engineering, 2025\
**The National Institute of Engineering, Mysuru**, BE in Computer Science, 2021
