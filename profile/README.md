# GAIMHE (Generative AI et Modèles Hybride pour l’Education)

## Overview

GAIMHE aims to design and evaluate hybrid EdTech architectures that combine:

- Frugal and pedagogically robust Intelligent Tutoring Systems (ITS) for macro-level orchestration
- Generative AI (LLM/SLM) for micro-level personalized feedback and content generation

This hybrid approach leverages the strengths of both paradigms to scale learning experiences, ensure pedagogical quality, and reduce computational costs compared to full-LLM solutions.

---

## Project Architecture

### 1. Macro Layer – Pre-generated Content
- Generation of large banks of pedagogical exercises, feedback, and hints using LLMs (e.g., Llama 3, GPT-4, Claude, Gemini)
- Orchestration with classical AI techniques
- Human expert validation of generated content
- Content stored and reused to minimize live calls to LLMs

### 2. Micro Layer – Real-time Generation with SLM
- Targeted use of SLM such as Mistral 7B, Llama 3 8B, or Phi 3 mini
- Activation in specific situations:
  - When a learner is stuck after multiple attempts
  - For open-ended or complex activities (e.g., text production, metacognition tasks)
- Ensures personalized and adaptive support while preserving efficiency

---

## Data Generation and Evaluation

- Pre-generation of pedagogical datasets using LLMs and expert validation
- Development of annotation protocols and codebooks to ensure quality and reliability
- Automatic generation and annotation of large-scale synthetic datasets using prompt engineering, RAG, in-context learning, and RLHF
- Collaboration with OpenLLM-France for SLM fine-tuning and benchmarking

---

## Environmental and Computational Impact

The hybrid approach is estimated to be around 30 times more efficient than full-LLM approaches.  
It is scalable to millions of learners with significantly reduced environmental impact.

---

## Collaborations

- EvidenceB
- OpenLLM-France
- Région Île-de-France
- Academic and industrial EdTech community
