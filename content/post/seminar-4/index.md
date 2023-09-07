---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "HCIR Seminar 4"
subtitle: ""
summary: "本セミナーでは、Joemon M. Jose教授（グラスゴー大学）をお招きして、強化学習を用いた情報推薦システムに関するご講演をいただきます。"
authors: []
tags: []
categories: []
date: 2023-09-07T09:00:00+09:00
lastmod: 2023-09-07T09:00:00+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

**題目：** Contrastive State Augmentations for Reinforcement Learning-Based Recommender Systems

**講演者：** Joemon M. Jose教授（グラスゴー大学）

**日時：** 2023年9月28日（木）15:00-16:00

**会場：** オンライン（Zoom）

**概要：** With the University of Tsukuba and the University of Glasgow engaging in a strategic partnership or collaborative undertaking, I will present the School of Computer Science and its research initiatives. Subsequently, I will discuss a recent study published at SIGIR (Special Interest Group on Information Retrieval)'23 Conference.

Learning reinforcement learning (RL)--based recommenders from historical user-item interaction sequences is vital to generate high-reward recommendations and improve long-term cumulative benefits. However,  existing RL recommendation methods encounter difficulties: (i) to estimate the value functions for states which are not contained in the offline training data, and (ii) to learn effective state representations from user implicit feedback due to the lack of contrastive signals.

We propose contrastive state augmentations (CSA) for the training of RL-based recommender systems.  To tackle the first issue, we propose four state augmentation strategies to enlarge the state space of the offline data. The proposed method improves the generalization capability of the recommender by making the RL agent visit the local state regions and ensuring the learned value functions are similar between the original and augmented states. For the second issue, we propose introducing contrastive signals between augmented states and the state randomly sampled from other sessions to improve the state representation learning further. 

To verify the effectiveness of the proposed CSA, we conduct extensive experiments on two publicly accessible datasets and one dataset collected from a real-life e-commerce platform. We also conduct experiments on a simulated environment as the online evaluation setting.  Experimental results demonstrate that CSA can effectively improve recommendation performance.

**講演者プロフィール：** Joemon Jose is a  Professor in the School of Computing Science at the University of Glasgow in Scotland. His past scholarly activities encompass a comprehensive interest in information retrieval, spanning theory, experimental methodologies, evaluation frameworks, and practical applications, all within textual and multimedia domains. At present, his research endeavours are advancing recommender techniques, with a particular emphasis on the intricate exploration of Deep Learning methodologies and Large Language Models (LLMs). He is a programme co-chair for CHIIR'24.

**対象者：** リサーチユニット構成員および指導学生

**参加方法：** Zoom URLをご連絡しますので、講演開始時刻までに参加ください。
