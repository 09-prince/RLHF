
# 🧠 Reinforcement Learning from Human Feedback (RLHF)

This repository contains experimental and production-ready implementations of **Reinforcement Learning from Human Feedback (RLHF)** techniques, focusing on:
- ✅ Direct Preference Optimization (DPO)
- ✅ Proximal Policy Optimization (PPO)
- ✅ Sentiment-Aligned Language Model Fine-Tuning
- ✅ TRL + HuggingFace-based RLHF pipelines



##  📂 Folder Structure


```bash
RLHF/
│
├── DPO/             # DPO fine-tuning (Anthropic HH-RLHF or custom datasets)
├── PPO/             # PPO fine-tuning using reward models (IMDb, sentiment, etc.)
├── README.md        # Project overview and instructions
└── ...
```

## Setup

# 1. Clone the repository
git clone https://github.com/09-prince/RLHF.git

cd RLHF/DPO

cd RLHF/PPO

# 2. Install dependencies
pip install -r requirements.txt


## Authors

- Created by [09-prince](https://github.com/09-prince)
## 📚 Blog

- 🔹 [**Reinforcement Learning from Human Feedback – DPO Edition**](https://medium.com/@gourprince2004/reinforcement-learning-from-human-feedback-7dc0dc32fd4e)  
  Dive into how Direct Preference Optimization (DPO) is used to align large language models using pairwise human preferences instead of reward scores.

<!-- - 🔸 [Understanding PPO (Proximal Policy Optimization)](https://your-blog-link.com/ppo-post) *(Coming Soon)*  
  A step-by-step guide to PPO and how it fits into the RLHF pipeline. -->
