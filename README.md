<div align="center">

# Jay Shim

**ML Researcher · Continual Learning · Post-Training · VLA Models**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jayjshim)
[![Google Scholar](https://img.shields.io/badge/-Google%20Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com)
[![arXiv](https://img.shields.io/badge/-arXiv-B31B1B?style=flat&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.11653)
[![Blog](https://img.shields.io/badge/-Blog-2962FF?style=flat&logo=hashnode&logoColor=white)](https://shimboi.hashnode.dev)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:jshim1213@gmail.com)

</div>

---

I'm an undergrad researcher in the [LARG Lab](https://www.cs.utexas.edu/~pstone/research.shtml) at UT Austin (Turing Scholar, CS Honors), advised by [Prof. Peter Stone](https://www.cs.utexas.edu/~pstone/). I study how large models retain previously learned capabilities during sequential fine-tuning — a problem at the intersection of continual learning, reinforcement learning, and safe deployment.

---

## Research

#### Simple Recipe Works: VLAs are Natural Continual Learners with RL
Jiaheng Hu\*, **Jay Shim\***, Chen Tang, Yoonchang Sung, Bo Liu, Peter Stone, Roberto Martin-Martin

[![Paper](https://img.shields.io/badge/arXiv-2603.11653-B31B1B?style=flat-square)](https://arxiv.org/abs/2603.11653)
[![Code](https://img.shields.io/badge/GitHub-continual--vla--rl-181717?style=flat-square&logo=github)](https://github.com/UT-Austin-RobIn/continual-vla-rl)
[![Stars](https://img.shields.io/github/stars/UT-Austin-RobIn/continual-vla-rl?style=flat-square)](https://github.com/UT-Austin-RobIn/continual-vla-rl)

We show that simple sequential LoRA fine-tuning with RL avoids catastrophic forgetting in VLAs, matching or outperforming dedicated continual learning methods (EWC, Experience Replay, Weight Merge). Built a distributed training framework extending RLinf with custom post-training techniques and efficient dataloaders. Scaled JAX training infrastructure by **1000x** via XLA profiling and JIT compilation redesign.

#### Contrastive Decoding for Improved CoT Reasoning in LLMs
**Jay Shim** et al. · *SoCal NLP Symposium 2024*

Zero-shot inference-time decoding method achieving **~6% improvement** on reasoning benchmarks (GSM8K, HotpotQA, CommonsenseQA) with Mistral-7B and Phi-1.5.

---

## Selected Projects

<table>
  <tr>
    <td><b><a href="https://github.com/UT-Austin-RobIn/continual-vla-rl">continual-vla-rl</a></b></td>
    <td>Continual RL for VLAs — PPO, GRPO, 5 CRL baselines on LIBERO. 196 commits, open-sourced.</td>
  </tr>
  <tr>
    <td><b><a href="https://github.com/ShimBoi/MJX-PureJaxRL">MJX-PureJaxRL</a></b></td>
    <td>GPU-accelerated RL — 50M env steps in 15 min via MJX + PureJaxRL integration.</td>
  </tr>
  <tr>
    <td><b><a href="https://github.com/ShimBoi/AttentionIsAllYouNeed">AttentionIsAllYouNeed</a></b></td>
    <td>Full Transformer reimplementation from scratch — 15.34 BLEU on WMT'14 DE→EN.</td>
  </tr>
</table>

---

## Tech Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JAX](https://img.shields.io/badge/-JAX-A435F0?style=flat-square)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Slurm](https://img.shields.io/badge/-Slurm-326CE5?style=flat-square)
![Ray](https://img.shields.io/badge/-Ray-028CF0?style=flat-square)

---

## Writing

- [Dedication is All We Need: Recreating the Original Transformer](https://medium.com/@jshim1213/dedication-is-all-we-need-recreating-the-original-transformer-2c29298eae63)

---

<div align="center">

**B.S. Computer Science Honors (Turing Scholar) · UT Austin · GPA 3.97/4.00**

</div>
