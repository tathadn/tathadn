## Hi, I'm Tathagata Debnath (Dave)

PhD candidate in Computer Science at New Mexico State University. I build agentic AI systems and fine-tune foundation models on multi-GPU infrastructure. My research background is in bioinformatics and algorithm design (10 publications, 80+ citations, IEEE TPAMI, Nature, & IEEE/ACM TCBB).

Currently focused on autonomous code debugging agents, vision-language model adaptation, and self-improving LLM systems using MCTS, DPO, and LoRA/QLoRA on distributed H100 setups.

---

### Featured Projects

**[CodeQ](https://github.com/tathadn/codeq)** — Autonomous code debugging agent using Monte Carlo Tree Search + Direct Preference Optimization. The model explores fix strategies via MCTS, critiques them with dual-temperature self-evaluation, and improves each round through DPO fine-tuning. Built on Qwen2.5-Coder-7B across two H100 nodes (4-bit inference + bf16 training). Achieved 81.3% fix rate on DebugBench (up from 10% pre-refactor), with DPO pushing MCTS mode to 84%.

**[Parallel Multi-Agent Codegen](https://github.com/tathadn/parallel-multi-agent-codegen)** — DAG-based multi-agent code generation system using LangGraph + native Anthropic SDK. Orchestrates parallel async workers that plan, generate, and review code through structured handoffs.

**[Self-Evolving Codegen](https://github.com/tathadn/self-evolving-codegen)** — Extension of the multi-agent pipeline with an LLM-as-Judge evaluator and autonomous prompt evolution loop. The system iteratively rewrites its own generation prompts based on evaluation feedback.

---

### Publications & Packages

- 10 peer-reviewed publications | 80+ citations — [Google Scholar](https://scholar.google.com/citations?user=AAErR7QAAAAJ&hl=en)
- **OptCirClust** — Fast optimal circular clustering algorithm (CRAN R package)
- **CircularSilhouette** — Circular silhouette index for cluster validation (CRAN R package)

---

### Links

[Website](https://tathagatadebnath.com) · [Google Scholar](https://scholar.google.com/citations?user=AAErR7QAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/tathagata-debnath-1a68727a/)
