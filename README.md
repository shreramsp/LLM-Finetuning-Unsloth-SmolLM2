# LLM Fine-tuning with Unsloth & SmolLM2-135M

This repository demonstrates **5 different LLM training techniques** using Unsloth AI and SmolLM2-135M (135 million parameter model). Each notebook covers a distinct fine-tuning methodology with practical implementations on free Google Colab GPUs.

---

## 📚 Notebooks & Video Tutorials

| # | Colab Name | Colab Link | YouTube Video |
|---|------------|------------|---------------|
| 1 | High-Rank LoRA Fine-tuning (r=128) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1V2TebLm95HPQDxBi-h09eo3NQ_MhvUON?usp=sharing) | [![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/BXV1xcY1X3A) |
| 2 | Standard LoRA Fine-tuning (r=16) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uWcJhiGoFRFwT3t7z8pmN1YboR_wCcRX?usp=sharing) | [![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/eWU3ERqTWY0) |
| 3 | DPO (Direct Preference Optimization) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YvM4_9_kF1Yw_4IHUOqQ4WV07QSx_Ziq?usp=sharing) | [![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/RBpjpN_zEtw) |
| 4 | GRPO (Group Relative Policy Optimization) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xEaLkkp8i01wc1RFUHSaGDWXoy5_IfNA?usp=sharing) | [![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/9yaR7Y2gPGQ) |
| 5 | Continued Pre-training | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JbmE2GUwXZtEqWBVM7dWvQfUthFrV09S?usp=sharing) | [![Watch Video](https://img.shields.io/badge/YouTube-Watch-red)](https://youtu.be/NdYcdqZ4GK0) |

---

## 📋 Detailed Overview

### **Colab 1: High-Rank LoRA Fine-tuning (r=128)**
- **Method:** Fuller fine-tuning with high-rank LoRA
- **Dataset:** Python coding instructions (18k examples)
- **Training:** ~10 minutes | 3.5% parameters trained
- **Use Case:** Task specialization with more parameter updates

### **Colab 2: Standard LoRA Fine-tuning (r=16)**
- **Method:** Parameter-efficient fine-tuning with standard LoRA
- **Dataset:** Python coding instructions (same as Colab 1)
- **Training:** ~8 minutes | 3.5% parameters trained
- **Use Case:** Efficient production deployment

### **Colab 3: DPO (Direct Preference Optimization)**
- **Method:** Reinforcement learning from preference pairs
- **Dataset:** Capybara DPO dataset (1,000 chosen/rejected pairs)
- **Training:** ~5 minutes | Preference-based learning
- **Use Case:** Alignment, safety, helpfulness optimization

### **Colab 4: GRPO (Group Relative Policy Optimization)**
- **Method:** Reasoning model training with reward-based learning
- **Dataset:** GSM8K math problems (50 examples)
- **Training:** ~3.6 minutes | Self-generated responses + rewards
- **Use Case:** Math reasoning, verifiable tasks

### **Colab 5: Continued Pre-training**
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

1. Click on any **Colab Link** to open the notebook
2. Run all cells sequentially in Google Colab
3. Watch the corresponding **YouTube Video** for detailed walkthrough
4. All training runs on free T4 GPU (no setup required)

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

## 🔗 Resources

- **Unsloth Documentation:** https://docs.unsloth.ai/
- **SmolLM2 Model:** https://huggingface.co/HuggingFaceTB/SmolLM2-135M-Instruct
- **TRL Library:** https://huggingface.co/docs/trl/

---

## 📝 License

MIT License - Feel free to use for educational purposes

---

## 🌟 Acknowledgments

- Unsloth AI for fast training library
- Hugging Face for SmolLM2 model
- Google Colab for free GPU resources

---
