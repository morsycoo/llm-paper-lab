# LLM Research Papers: From Theory to Practice

A hands-on learning repository dedicated to studying, implementing, and evaluating foundational research papers in Large Language Models (LLMs).

The goal is to move beyond reading papers by building practical implementations, running reproducible experiments, measuring results, and documenting engineering decisions.

## Objectives

- Understand the core ideas behind modern Transformer-based language models.
- Implement key techniques using Python and PyTorch.
- Explore Retrieval-Augmented Generation (RAG), reasoning, and AI agents.
- Experiment with parameter-efficient fine-tuning and preference optimization.
- Evaluate model behavior using measurable metrics and controlled experiments.
- Build practical projects that demonstrate research understanding and AI engineering skills.

## Research Papers

| # | Paper | Main Focus | Planned Practical Application |
|---|---|---|---|
| 01 | [Attention Is All You Need](https://arxiv.org/abs/1706.03762) | Transformer architecture and self-attention | Mini Transformer implementation |
| 02 | [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401) | Retrieval-Augmented Generation (RAG) | Personal Knowledge Assistant |
| 03 | [Lost in the Middle: How Language Models Use Long Contexts](https://arxiv.org/abs/2307.03172) | Long-context behavior and evidence position | Context Position Evaluation Lab |
| 04 | [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903) | Multi-step prompting and reasoning | Prompting Evaluation Benchmark |
| 05 | [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) | Tool-using language model agents | Research Agent |
| 06 | [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) | Parameter-efficient fine-tuning | LoRA Fine-Tuning Experiment |
| 07 | [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155) | Supervised fine-tuning and RLHF | Preference Learning Experiment |
| 08 | [Direct Preference Optimization: Your Language Model Is Secretly a Reward Model](https://arxiv.org/abs/2305.18290) | Direct preference optimization | DPO Fine-Tuning Experiment |

## Study Plan

- **Duration:** 47 days
- **Daily commitment:** 2 hours
- **Total planned effort:** 94 hours

The schedule combines paper reading, implementation, experimentation, evaluation, and documentation.

The timeline is a working target. Individual experiments may require adjustments depending on implementation complexity and available computing resources.

## Repository Structure

```text
llm-paper-lab/
├── papers/
│   ├── 01-transformer.md
│   ├── 02-rag.md
│   ├── 03-lost-in-the-middle.md
│   ├── 04-chain-of-thought.md
│   ├── 05-react.md
│   ├── 06-lora.md
│   ├── 07-instructgpt.md
│   └── 08-dpo.md
├── experiments/
├── src/
├── eval/
├── reports/
├── requirements.txt
└── README.md
```

The structure will evolve as implementations and experiments are added.

## Engineering Principles

Each paper will be approached through four stages:

1. **Understand:** Identify the research problem, proposed method, assumptions, and limitations.
2. **Implement:** Build a minimal working implementation or reproduce a relevant experiment.
3. **Evaluate:** Compare against a baseline using appropriate metrics and controlled tests.
4. **Document:** Record findings, failures, limitations, and engineering decisions.

Not every paper requires a standalone production application. Some are better explored through controlled experiments, benchmarks, or small research implementations.

## Evaluation Criteria

Experiments will use appropriate measurements depending on the task, including:

- Accuracy and task completion rate.
- Retrieval relevance and answer correctness.
- Latency and token usage.
- Training cost and trainable parameter count.
- Robustness, reproducibility, and failure analysis.

Results will be reported only after experiments have been executed. Planned work will be distinguished from completed implementations.

## Technology Stack

The expected tools include:

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face PEFT
- Vector search and embedding libraries
- Jupyter Notebooks
- Git and GitHub

Additional libraries and infrastructure will be selected according to each experiment.

## Final Project

The planned capstone is a **Personal Knowledge AI Assistant with Research and Tool-Using Capabilities**.

It will explore how retrieval, context management, tool use, and systematic evaluation can be combined into a practical LLM-powered system.

Fine-tuning and preference optimization will be incorporated only where experiments justify their use and available resources permit.

## Current Status

**Status:** In Progress

This repository is currently a learning and experimentation project. Implementations, benchmarks, and results will be added progressively as each research paper is studied.

## License

A license will be selected when the repository's code and documentation are ready for public release. The original research papers remain the property of their respective authors and publishers.
