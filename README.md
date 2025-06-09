<h1 align="center">
Infi-MMR: Curriculum-based Unlocking Multimodal Reasoning via Phased Reinforcement Learning in Multimodal Small Language Models
</h1>

<p align="center">
  <a href="https://arxiv.org/abs/2505.23091"><img src="https://img.shields.io/badge/arXiv-Paper-b31b1b?style=flat&logo=arxiv&logoColor=white" alt="arXiv Paper"></a>
  <a href="https://huggingface.co/papers/2504.14239"><img src="https://img.shields.io/badge/🤗%20HuggingFace-Daily%20Papers-ff9800?style=flat" alt="Hugging Face Paper"></a>
  <a href="https://huggingface.co/Reallm-Labs/Infi-MMR-3B"><img src="https://img.shields.io/badge/🤗%20HuggingFace-Models-ff9800?style=flat" alt="Hugging Face Model"></a>
</p>

<br>
<p align="center">
  <strong>This is the official repository for the paper <a href="https://arxiv.org/abs/2505.23091">Infi-MMR-3B</a>.</strong>
</p>

## 🌟 Overview
In this work, we design a novel framework, **Infi-MMR**, to systematically unlock the reasoning potential of Multimodal Small Language Models (MSLMs) through a curriculum of three carefully structured phases and propose our multimodal reasoning model **Infi-MMR-3B**.

Specially, **Infi-MMR**,  a curriculum-based progressive rule-based RL training framework that unfolds in three distinct phases:
- **Foundational Reasoning Activation** leverages high-quality textual reasoning datasets to activate and strengthen the model’s logical reasoning capabilities.
- **Cross-Modal Reasoning Adaptation** utilizes caption-augmented multimodal data to facilitate the progressive transfer of reasoning skills to multimodal contexts.
- **Multimodal Reasoning Enhancement**  employs curated, caption-free multimodal data to mitigate linguistic biases and promote robust cross-modal reasoning.

