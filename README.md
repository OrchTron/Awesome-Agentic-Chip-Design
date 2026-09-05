# Awesome Agentic Chip Design

A curated list of papers, benchmarks, and systems for agentic chip design. This repository focuses on LLM agents, reinforcement learning, and automated workflows for hardware design, verification, debugging, and architecture exploration.

## Contents

- [Awesome Agentic Chip Design](#awesome-agentic-chip-design)
  - [Contents](#contents)
  - [Must-Reads](#must-reads)
  - [Papers](#papers)
    - [Surveys](#surveys)
    - [Benchmarks and Evaluation](#benchmarks-and-evaluation)
    - [RTL Generation and Optimization](#rtl-generation-and-optimization)
    - [EDA Flow Optimization](#eda-flow-optimization)
    - [Architecture Exploration](#architecture-exploration)
  - [Contributing](#contributing)

## Must-Reads

- [The Dawn of Agentic EDA: A Survey of Autonomous Digital Chip Design](https://arxiv.org/abs/2512.23189) | arXiv 2025
- [HWE-Bench: Benchmarking LLM Agents on Real-World Hardware Bug Repair Tasks](https://arxiv.org/abs/2604.14709) | arXiv 2026
- [ORFS-agent: Tool-Using Agents for Chip Design Optimization](https://arxiv.org/abs/2506.08332) | arXiv 2025

## Papers

### Surveys

- [The Dawn of Agentic EDA: A Survey of Autonomous Digital Chip Design](https://arxiv.org/abs/2512.23189) | arXiv 2025 | Tsientang Institute for Advanced Study, Zhejiang University
  - Surveys the shift from traditional CAD and AI-assisted EDA toward AI-native and agentic digital chip design across RTL generation, verification, physical design, and tool orchestration.
- [Agentic Electronic Design Automation: A Handoff Perspective](https://arxiv.org/abs/2606.19795) | arXiv 2026 | The Chinese University of Hong Kong, Primarius Technologies
  - Reviews 82 agentic EDA systems through stage-, flow-, and organization-bound handoffs, and proposes a five-layer EDA Agent Communication Protocol for portable, auditable, and secure workflows.

### Benchmarks and Evaluation

- [HWE-Bench: Benchmarking LLM Agents on Real-World Hardware Bug Repair Tasks](https://arxiv.org/abs/2604.14709) | arXiv 2026 | Peking University
  - Introduces a repository-level benchmark for evaluating LLM agents on real hardware bug repair tasks across Verilog/SystemVerilog and Chisel projects.
- [Rule2DRC: Benchmarking LLM Agents for DRC Script Synthesis with Execution-Guided Test Generation](https://arxiv.org/abs/2605.15669) | ICML 2026 | Seoul National University, Samsung Electronics
  - Introduces 1,000 natural-language-to-DRC-script tasks with 13,921 evaluation layouts and an execution-guided tester agent for selecting functionally correct scripts.
- [PDAgent-Bench: Characterizing, Grounding, and Architecting LLM/VLM Agents for VLSI Physical Design](https://arxiv.org/abs/2606.17253) | arXiv 2026 | George Washington University, Brown University, UCLA, NVIDIA, The University of Texas at Austin
  - Introduces a 353-task benchmark and tool-integrated multi-agent framework for evaluating physical-design knowledge, report comprehension, root-cause analysis, EDA script generation, and full RTL-to-GDSII execution.
- [Can AI Agents Really Complete RTL-to-GDS? Lessons from Benchmarking Tool-Interactive EDA Workflows](https://arxiv.org/abs/2607.17528) | arXiv 2026 | Zhejiang University, ChipFlux
  - Benchmarks general-purpose coding agents, EDA skill-augmented agents, and structured execution infrastructure on end-to-end PicoRV32 RTL-to-GDS flows, highlighting stage completion, Token ROI, and tool-interface reliability.

### RTL Generation and Optimization

- [Spec2RTL-Agent: Automated Hardware Code Generation from Complex Specifications Using LLM Agent Systems](https://arxiv.org/abs/2506.13905) | arXiv 2025 | NVIDIA Research, Cadence, Georgia Institute of Technology
  - Proposes an LLM agent system that processes complex specification documents and generates corresponding RTL implementations.
- [Dr. RTL: Autonomous Agentic RTL Optimization through Tool-Grounded Self-Improvement](https://arxiv.org/abs/2604.14989) | arXiv 2026 | Hong Kong University of Science and Technology
  - Presents a multi-agent RTL timing optimization framework with critical-path analysis, parallel rewriting, tool-based evaluation, and reusable optimization skills.

### EDA Flow Optimization

- [ORFS-agent: Tool-Using Agents for Chip Design Optimization](https://arxiv.org/abs/2506.08332) | arXiv 2025 | UC San Diego
  - Introduces an LLM-based tool-using agent for iterative parameter tuning in open-source chip design flows, improving routed wirelength and effective clock period with fewer optimization iterations.

### Architecture Exploration

- [From LLM to Silicon: RL-Driven ASIC Architecture Exploration for On-Device AI Inference](https://arxiv.org/abs/2604.07526) | arXiv 2026 | XgenSilicon
  - Presents an RL-driven compiler that jointly optimizes ASIC architecture, memory hierarchy, and workload partitioning for on-device AI inference.
- [Design Conductor 2.0: An Agent Builds a TurboQuant Inference Accelerator in 80 Hours](https://arxiv.org/abs/2605.05170) | arXiv 2026 | Verkor
  - Presents a long-running multi-agent system that autonomously translates high-level concepts into verified hardware designs, including a TurboQuant accelerator mapped to FPGA and evaluated in TSMC 16FF.

## Contributing

Contributions are welcome. Please open an issue or pull request if you would like to add a relevant paper, benchmark, tool, dataset, or project related to agentic chip design.
