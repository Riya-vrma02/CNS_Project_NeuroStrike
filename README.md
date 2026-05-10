# CNS_Project_NeuroStrike
# NeuroStrike: Neuron-Level Attacks on Aligned LLMs

A research project and implementation study on **Neuron-Level Attacks against Aligned Large Language Models (LLMs)** based on the NeuroStrike framework.

---

## Project Overview

Modern Large Language Models (LLMs) use alignment techniques such as RLHF, supervised fine-tuning, and safety filters to prevent harmful outputs.

This project studies **NeuroStrike**, a neuron-level attack framework that targets internal neurons associated with safety behaviors inside aligned LLMs.

Instead of relying only on prompt engineering attacks, NeuroStrike manipulates internal neuron activations to weaken alignment mechanisms while preserving most normal model functionality.

The project explains:

- How safety-related neurons are identified
- How neuron activations are manipulated
- Alignment bypass mechanisms
- Experimental workflow and observations
- Challenges and mitigation techniques

---

## Objectives

- Understand neuron-level attacks in aligned LLMs
- Analyze safety-related neuron behavior
- Study alignment bypass through neuron manipulation
- Evaluate attack effectiveness
- Compare model outputs before and after manipulation
- Explore mitigation techniques for internal attacks
- Understand security implications for real-world AI systems

---

## NeuroStrike Workflow

The framework operates in two major stages:

### 1. Neuron Identification
- Analyze neuron activations for safe and unsafe prompts
- Detect neurons correlated with refusal/safety behavior

### 2. Neuron Manipulation
- Suppress or perturb targeted neurons
- Generate responses with weakened safety alignment

---

## System Architecture

The project workflow contains the following modules:

1. Input Prompt Module  
2. LLM Inference Engine  
3. Neuron Activation Analyzer  
4. Safety Neuron Detector  
5. Neuron Manipulation Layer  
6. Output Evaluation System  

---

## Implementation Steps

1. Load an aligned pre-trained LLM
2. Run safe and unsafe prompts
3. Record neuron activation patterns
4. Detect influential safety neurons
5. Apply neuron perturbation/suppression
6. Generate manipulated outputs
7. Evaluate:
   - Attack Success Rate (ASR)
   - Response Quality
   - Alignment Robustness
   - Computational Overhead
8. Compare outputs before and after attack

---

## Key Findings

- Small neuron modifications can significantly affect alignment
- Safety behaviors are concentrated in limited neuron groups
- Internal attacks may bypass safeguards more effectively than prompt attacks
- Model quality is mostly preserved after manipulation
- Current aligned LLMs remain vulnerable to neuron-level attacks

---

## Mitigation Techniques

Possible defenses against neuron-level attacks include:

- Distributed safety representations
- Adversarial training
- Activation consistency monitoring
- Dynamic alignment mechanisms
- Continuous security auditing
- Detection of abnormal neuron activations

---

## Repository Structure

```bash
├── report/
│   └── CNS_Project_Report.pdf
├── images/
│   └── experimental_results/
├── src/
│   └── implementation_files
├── README.md
```

---

## Experimental Results

Add screenshots, graphs, and output images inside the `images/` directory.

Example:

- Attack output screenshots
- Neuron activation visualizations
- Safety bypass comparisons
- ASR performance graphs

---

## Research Paper Reference

- NeuroStrike Research Paper
- GitHub Repository:  
  https://github.com/wu-lichao/NeuroStrike-Neuron-Level-Attacks-on-Aligned-LLMs

---

##  Authors

- Riya Verma
- Akhila Jukuri

Submitted to: **Ramesh Babu Battula**  
May 2026

---
