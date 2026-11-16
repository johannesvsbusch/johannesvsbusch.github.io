---
title: "Temperature Guidance for Robust Reward Conditioning in Diffusion Planning"
authors:
  - me
  - Roberto Calandra
date: 2026-12-01
publishDate: 2026-11-01   # page is shown from this day on; `date` is the conference date
publication_type: conference
status: accepted   # shown in brackets after the venue; delete this line once published
venue:
  name: "Advances in Neural Information Processing Systems"
  short: "NeurIPS"
links:
  - name: PDF
    url: https://openreview.net/forum?id=PHxRfWn3K5
tags:
  - Reinforcement Learning
  - Generative Modelling
abstract: |-
  Diffusion planners enable long-horizon planning through a generative process over full trajectories, mitigating compounding errors of autoregressive methods while handling multimodal futures. Reward conditioning via classifier-free guidance (CFG) yields high-performing plans but is brittle with respect to per-task hyperparameter choices, limiting its scalability. Our analysis reveals that guidance performance hinges on careful adaptation to the data manifold and reward distribution, contributing to CFG's hyperparameter fragility. We propose temperature-guided diffusion planning (TGDP), which adapts CFG to self-calibrate to these characteristics through temperature-conditioned sample reweighting during training and adaptive guidance at inference. TGDP mitigates the hyperparameter fragility of CFG and achieves competitive performance across standard benchmarks without per-task tuning, thus enabling more robust and practical diffusion-based planning.
---
