# Awesome VLM-RL
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
![GitHub stars](https://img.shields.io/github/stars/steve-zeyu-zhang/Awesome-VLM-RL?color=yellow)
![GitHub forks](https://img.shields.io/github/forks/steve-zeyu-zhang/Awesome-VLM-RL?color=9cf)

This is the github repository for the survey paper:
> **Reinforcement Learning for Visual-Language Models: A Survey**
> 
> Authors et al.
>  
> [**[arXiv]**]()
>

```
@misc{VLM_RL,
	title = {Reinforcement Learning for Visual-Language Models: A Survey},
	url = {https://github.com/steve-zeyu-zhang/Awesome-VLM-RL},
	author = {Author et al.},
	date = {2025-02-28},
	year = {2025},
	month = {2},
	day = {28},
}
```

Welcome to follow and star!

## Introduction

Multi-Modal RL agents focus on learning from video (images), language (text), or both, as humans do. We believe that it is important for intelligent agents to learn directly from images or text, since such data can be easily obtained from the Internet.

![飞书20220922-161353](https://user-images.githubusercontent.com/4834562/191696555-2ff17e41-77f4-4d04-ba2a-ea9bc8d99d96.png)

## Table of Contents

- [Awesome Multi-Modal Reinforcement Learning](#awesome-multi-modal-reinforcement-learning)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [Papers](#papers)
    - [General-RL](#General-RL)
    - [VLM-RL](#VLM-RL)
    - [Generative-RL](#Generative-RL)
  - [Contributing](#contributing)

## Papers

```
format:
- [title](paper link) [links]
  - authors.
  - key words.
  - experiment environment.
```

### General-RL

- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155)  
  - Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, Ryan Lowe

- [Reinforcement Learning with Human Feedback: Learning Dynamic Choices via Pessimism](https://arxiv.org/abs/2305.18438)  
  - Zihao Li, Zhuoran Yang, Mengdi Wang

- [RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback](https://arxiv.org/abs/2309.00267)  
  - Harrison Lee, Samrat Phatale, Hassan Mansoor, Thomas Mesnard, Johan Ferret, Kellie Lu, Colton Bishop, Ethan Hall, Victor Carbune, Abhinav Rastogi, Sushant Prakash


- [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)  
  - John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, Oleg Klimov

- [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290)  
  - Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn
 
- [SimPO: Simple Preference Optimization with a Reference-Free Reward](https://arxiv.org/abs/2305.18290)  
  - Yu Meng, Mengzhou Xia, Danqi Chen
 
- [Nash Learning from Human Feedback](https://arxiv.org/abs/2312.00886)
  - Rémi Munos, Michal Valko, Daniele Calandriello, Mohammad Gheshlaghi Azar, Mark Rowland, Zhaohan Daniel Guo, Yunhao Tang, Matthieu Geist, Thomas Mesnard, Andrea Michi, Marco Selvi, Sertan Girgin, Nikola Momchev, Olivier Bachem, Daniel J. Mankowitz, Doina Precup, Bilal Piot
 
- [Noise Contrastive Alignment of Language Models with Explicit Rewards](https://arxiv.org/abs/2402.05369)
  - Huayu Chen, Guande He, Lifan Yuan, Ganqu Cui, Hang Su, Jun Zhu
 
- [KTO: Model Alignment as Prospect Theoretic Optimization](https://arxiv.org/abs/2402.01306)
  - Kawin Ethayarajh, Winnie Xu, Niklas Muennighoff, Dan Jurafsky, Douwe Kiela

- [Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models](https://arxiv.org/abs/2401.01335)
  - Zixiang Chen, Yihe Deng, Huizhuo Yuan, Kaixuan Ji, Quanquan Gu

- [Iterative Reasoning Preference Optimization](https://arxiv.org/abs/2404.19733v1)
  - Richard Yuanzhe Pang, Weizhe Yuan, Kyunghyun Cho, He He, Sainbayar Sukhbaatar, Jason Weston
 
- [Trust Region Policy Optimization](https://arxiv.org/abs/1502.05477)  
  - John Schulman, Sergey Levine, Philipp Moritz, Michael I. Jordan, Pieter Abbeel
 
- [ORPO: Monolithic Preference Optimization without Reference Model](https://arxiv.org/abs/2403.07691)  
  - Jiwoo Hong, Noah Lee, James Thorne
 
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)  
  - Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao
 
- [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366)  
  - Noah Shinn, Federico Cassano, Edward Berman, Ashwin Gopinath, Karthik Narasimhan, Shunyu Yao
 
- [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050)  
  - Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe
 
- [OpenR: An Open Source Framework for Advanced Reasoning with Large Language Models](https://arxiv.org/abs/2305.20050)  
  - Jun Wang, Meng Fang, Ziyu Wan, Muning Wen, Jiachen Zhu, Anjie Liu, Ziqin Gong, Yan Song, Lei Chen, Lionel M. Ni, Linyi Yang, Ying Wen, Weinan Zhang

- [O1 Replication Journey: A Strategic Progress Report -- Part 1](https://arxiv.org/abs/2410.18982)  
  - Yiwei Qin, Xuefeng Li, Haoyang Zou, Yixiu Liu, Shijie Xia, Zhen Huang, Yixin Ye, Weizhe Yuan, Hector Liu, Yuanzhi Li, Pengfei Liu
  
- [O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple Distillation, Big Progress or Bitter Lesson?](https://arxiv.org/abs/2411.16489v1)  
  - Zhen Huang, Haoyang Zou, Xuefeng Li, Yixiu Liu, Yuxiang Zheng, Ethan Chern, Shijie Xia, Yiwei Qin, Weizhe Yuan, Pengfei Liu
 
- [O1 Replication Journey -- Part 3: Inference-time Scaling for Medical Reasoning](https://arxiv.org/abs/2501.06458)  
  - Zhongzhen Huang, Gui Geng, Shengyi Hua, Zhen Huang, Haoyang Zou, Shaoting Zhang, Pengfei Liu, Xiaofan Zhang
 
- [Triple Preference Optimization: Achieving Better Alignment using a Single Step Optimization](https://arxiv.org/abs/2405.16681)  
  - Amir Saeidi, Shivanshu Verma, Aswin RRV, Kashif Rasul, Chitta Baral
 
- [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300)  
  - Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Xiao Bi, Haowei Zhang, Mingchuan Zhang, Y.K. Li, Y. Wu, Daya Guo
  
- [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948)  
  - DeepSeek-AI
  
### VLM-RL
- [Fine-Tuning Large Vision-Language Models as Decision-Making Agents via Reinforcement Learning](https://arxiv.org/abs/2405.10292)
  - Yuexiang Zhai, Hao Bai, Zipeng Lin, Jiayi Pan, Shengbang Tong, Yifei Zhou, Alane Suhr, Saining Xie, Yann LeCun, Yi Ma, Sergey Levine


### Generative-RL
- [PaLI: A Jointly-Scaled Multilingual Language-Image Model](https://arxiv.org/abs/2209.06794)(**<font color="red">notable top 5%</font>**) 
  - Xi Chen, Xiao Wang, Soravit Changpinyo, AJ Piergiovanni, Piotr Padlewski, Daniel Salz, Sebastian Goodman, Adam Grycner, Basil Mustafa, Lucas Beyer, Alexander Kolesnikov, Joan Puigcerver, Nan Ding, Keran Rong, Hassan Akbari, Gaurav Mishra, Linting Xue, Ashish Thapliyal, James Bradbury, Weicheng Kuo, Mojtaba Seyedhosseini, Chao Jia, Burcu Karagol Ayan, Carlos Riquelme, Andreas Steiner, Anelia Angelova, Xiaohua Zhai, Neil Houlsby, Radu Soricut
  - Keyword: amazing zero-shot, language component and visual component
  - ExpEnv: None

- [VIMA: General Robot Manipulation with Multimodal Prompts](https://arxiv.org/abs/2210.03094)
  - Yunfan Jiang, Agrim Gupta, Zichen Zhang, Guanzhi Wang, Yongqiang Dou, Yanjun Chen, Li Fei-Fei, Anima Anandkumar, Yuke Zhu, Linxi Fan. *NeurIPS Workshop 2022*
  - Key Words: multimodal prompts, transformer-based generalist agent model, large-scale benchmark
  - ExpEnv: [VIMA-Bench](https://github.com/vimalabs/VimaBench), [VIMA-Data](https://huggingface.co/datasets/VIMA/VIMA-Data)

- [MIND ’S EYE: GROUNDED LANGUAGE MODEL REASONING THROUGH SIMULATION](https://arxiv.org/abs/2210.05359)
  - Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai
  - Keyword:  language2physical-world, reasoning ability
  - ExpEnv: [MuJoCo](https://mujoco.org/)



## Contributing

Our purpose is to make this repo even better. If you are interested in contributing, please refer to [HERE](CONTRIBUTING.md) for instructions in contribution.
