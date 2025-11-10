# LLM Fine-tuning with Unsloth & SmolLM2-135M

This repository demonstrates **5 different LLM training techniques** using Unsloth AI and SmolLM2-135M (135 million parameter model). Each notebook covers a distinct fine-tuning methodology with practical implementations on free Google Colab GPUs.

---

## 📚 Notebooks & Video Tutorials

### **Colab 1: High-Rank LoRA Fine-tuning (r=128)**
[![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/BXV1xcY1X3A)
- **Method:** Fuller fine-tuning with high-rank LoRA
- **Dataset:** Python coding instructions (18k examples)
- **Training:** ~10 minutes | 3.5% parameters trained
- **Use Case:** Task specialization with more parameter updates

---

### **Colab 2: Standard LoRA Fine-tuning (r=16)**
[![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/eWU3ERqTWY0)
- **Method:** Parameter-efficient fine-tuning with standard LoRA
- **Dataset:** Python coding instructions (same as Colab 1)
- **Training:** ~8 minutes | 3.5% parameters trained
- **Use Case:** Efficient production deployment

---

### **Colab 3: DPO (Direct Preference Optimization)**
[![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/RBpjpN_zEtw)
- **Method:** Reinforcement learning from preference pairs
- **Dataset:** Capybara DPO dataset (1,000 chosen/rejected pairs)
- **Training:** ~5 minutes | Preference-based learning
- **Use Case:** Alignment, safety, helpfulness optimization

---

### **Colab 4: GRPO (Group Relative Policy Optimization)**
[![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/9yaR7Y2gPGQ)
- **Method:** Reasoning model training with reward-based learning
- **Dataset:** GSM8K math problems (50 examples)
- **Training:** ~3.6 minutes | Self-generated responses + rewards
- **Use Case:** Math reasoning, verifiable tasks

---

### **Colab 5: Continued Pre-training**
[![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/NdYcdqZ4GK0)
- **Method:** Domain knowledge expansion through raw text
- **Dataset:** Medical terminology texts (200 samples)
- **Training:** ~1.4 minutes | Language modeling objective
- **Use Case:** New languages, domain adaptation, knowledge updates

---

## 🎯 Training Techniques Summary

| Colab | Method | Input Type | Goal | Training Time |
|-------|--------|------------|------|---------------|
| 1 | High-Rank LoRA | Instruction pairs | Fuller fine-tuning | ~10 min |
| 2 | Standard LoRA | Instruction pairs | Efficient fine-tuning | ~8 min |
| 3 | DPO | Chosen/Rejected pairs | Preference learning | ~5 min |
| 4 | GRPO | Prompts only | Reasoning training | ~3.6 min |
| 5 | Continued Pre-training | Raw text | Knowledge expansion | ~1.4 min |

---

## 🚀 Quick Start

1. Open any notebook in Google Colab
2. Run all cells sequentially
3. Watch the corresponding video tutorial
4. Training runs on free T4 GPU

---

## 🛠️ Tech Stack

- **Model:** SmolLM2-135M-Instruct (135M parameters)
- **Library:** Unsloth AI (2x faster training)
- **Framework:** Transformers, TRL, PEFT
- **Hardware:** Google Colab T4 GPU (free tier)

---

## 📊 Results

- ✅ All models trained successfully on free GPUs
- ✅ Training times: 1.4 - 10 minutes per notebook
- ✅ Demonstrates 5 distinct LLM training methodologies
- ✅ Practical implementations with real datasets

---

## 🎓 Learning Outcomes

- Understand difference between fine-tuning methods
- Compare LoRA rank effects (r=16 vs r=128)
- Learn reinforcement learning (DPO, GRPO)
- Explore continued pre-training for domain adaptation
- Hands-on experience with modern LLM training

---
