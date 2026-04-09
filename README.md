# Prot2Chat-Tropical 

**A Domain-Specific Multimodal Q&A System for Endemic Pathogens in Bangladesh**

Prot2Chat-Tropical is an ongoing research-driven project focused on building a specialized AI system that can interpret protein structures and answer biological questions related to region-specific pathogens such as **Dengue (Serotype 2)**, **Nipah**, and **Cholera**.

---

##  Overview

This project introduces a **multimodal Protein-LLM framework** that bridges structural biology and natural language understanding. It enables context-aware explanations of protein mutations and pathogen behavior that generic LLMs often fail to capture.

---

##  Key Features

*  **Multimodal Learning**: Integrates 3D protein structural data with language modeling
*  **Protein-Aware Reasoning**: Understands mutation-level variations in endemic pathogens
*  **Parameter-Efficient Fine-Tuning**: Uses LoRA for efficient adaptation
*  **Synthetic Data Pipeline**: Generates high-quality instruction-tuning data to address data scarcity

---

##  Architecture

* **Protein Encoder**: ProteinMPNN (frozen) for structural feature extraction
* **Language Model**: LLaMA-3 for domain-specific Q&A generation
* **Fine-Tuning**: LoRA-based parameter-efficient training

---

##  Data Pipeline

* Extracted structured biological features from:

  * UniProtKB
  * IEDB
* Generated **1,500+ instruction-tuning samples** using GPT-based curation
* Focused on mutation-specific and strain-aware explanations

---

##  Target Pathogens

* Dengue Virus (Serotype 2)
* Nipah Virus *(ongoing)*
* Vibrio cholerae *(ongoing)*

---

##  Tech Stack

* Python
* PyTorch
* ProteinMPNN
* LLaMA-3
* LoRA (PEFT)

---

##  Status

🚧 Ongoing — actively expanding dataset and improving multimodal alignment

---

##  Future Work

* Extend to additional tropical pathogens
* Improve 3D structure–text alignment
* Deploy as an interactive research assistant

---

##  Contributions

This is a research-focused project. Contributions, ideas, and collaborations are welcome.

