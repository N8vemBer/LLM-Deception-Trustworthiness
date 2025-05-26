# VeriGuard AI: Investigating AI Deception & Trustworthiness in LLM Agents

This repository accompanies the research paper submitted to the **AgentX Competition at UC Berkeley – May 2025**.

---

## 🧠 Project Summary

**VeriGuard AI** is a modular framework designed to **detect, classify, and mitigate deceptive outputs** in Large Language Models (LLMs) across high-stakes domains such as **law, medicine, and finance**. We introduce a three-part mitigation strategy combining:

- ✅ Self-Reflection Prompting  
- ✅ Cross-Verification with external databases  
- ✅ Confidence Calibration  

---

## 📄 Paper

The full PDF paper is available here:  
[`LLM - Investigating AI Deception & Trustworthiness in LLM Agents.pdf`](./LLM%20-%20Investigating%20AI%20Deception%20&%20Trustworthiness%20in%20LLM%20Agents.pdf)

---

## 📁 Repository Structure

```
LLM-Deception-Trustworthiness/
├── README.md
├── LLM - Investigating AI Deception & Trustworthiness in LLM Agents.pdf
├── /data/
│   ├── high_quality_prompts_sample.csv       # 500 realistic prompts + annotations
│   └── simulated_10000_prompts.csv           # 10,000 simulated samples (scale test)
├── /src/
│   └── main.py                               # Script placeholder for evaluation framework
├── /figures/
│   ├── figure_page_4.png                     # Framework overview
│   ├── figure_page_5.png                     # Deception rates
│   ├── figure_page_6.png                     # Strategy effectiveness
│   └── figure_page_7.png                     # Combined mitigation impact
├── /docs/                                    # Appendices, slides, or supplementary materials
```

---

## 📊 Benchmark Datasets

### ✅ High-Quality Prompt Sample
- 500 prompts across **Law, Medicine, Finance**
- Includes prompt texts, model used, deception type, mitigation strategy, and result  
➡️ [`high_quality_prompts_sample.csv`](./data/high_quality_prompts_sample.csv)

### 🔁 Simulated Evaluation Dataset
- 10,000 prompt-level evaluations with metadata
- Optimized for testing mitigation accuracy and performance at scale  
➡️ [`simulated_10000_prompts.csv`](./data/simulated_10000_prompts.csv)

---

## 📈 Figures from Paper

Key visual results included in the research paper:

- `figure_page_4.png` — Framework overview (Self-Reflection → Verification → Calibration)
- `figure_page_5.png` — Deception rate comparison (Baseline vs. Mitigated)
- `figure_page_6.png` — Individual mitigation effectiveness
- `figure_page_7.png` — Combined strategy impact (Ablation study)

---

## 🎥 Video Demo

🔗 https://youtu.be/SUf-V-r1TdM

---

## 📜 License

All code and data are shared for academic, evaluation, and non-commercial research use.  
Please contact the author for permissions beyond this scope.

---

## 🙋‍♂️ Author

Boecyàn Bourgade  
`VeriGuard AI – UC Berkeley AgentX Track`  
contact: boecyan[at]gmail[dot]com
