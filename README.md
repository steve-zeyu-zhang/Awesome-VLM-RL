# Awesome Multi-Modal Reinforcement Learning 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
![visitor badge](https://visitor-badge.lithub.cc/badge?page_id=opendilab.awesome-multi-modal-reinforcement-learning&left_text=Visitors)
[![docs](https://img.shields.io/badge/docs-latest-blue)](https://github.com/opendilab/awesome-multi-modal-reinforcement-learning)
![GitHub stars](https://img.shields.io/github/stars/opendilab/awesome-multi-modal-reinforcement-learning?color=yellow)
![GitHub forks](https://img.shields.io/github/forks/opendilab/awesome-multi-modal-reinforcement-learning?color=9cf)
[![GitHub license](https://img.shields.io/github/license/opendilab/awesome-multi-modal-reinforcement-learning)](https://github.com/opendilab/awesome-multi-modal-reinforcement-learning/blob/main/LICENSE)

This is a collection of research papers for **Multi-Modal reinforcement learning (MMRL)**.
And the repository will be continuously updated to track the frontier of MMRL.
Some papers may not be relevant to RL, but we include them anyway as they may be useful for the research of MMRL.

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
  - [License](#license)

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

- [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)  
  - John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, Oleg Klimov

- [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290)  
  - Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn
 
- [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300)  
  - Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Xiao Bi, Haowei Zhang, Mingchuan Zhang, Y.K. Li, Y. Wu, Daya Guo
  
- [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948)  
  - DeepSeek-AI
  
### VLM-RL
- [DrM: Mastering Visual Reinforcement Learning through Dormant Ratio Minimization](https://openreview.net/pdf?id=MSe8YFbhUE)
  - Guowei Xu, Ruijie Zheng, Yongyuan Liang, Xiyao Wang, Zhecheng Yuan, Tianying Ji, Yu Luo, Xiaoyu Liu, Jiaxin Yuan, Pu Hua, Shuzhen Li, Yanjie Ze, Hal Daumé III, Furong Huang, Huazhe Xu
  - Keyword: Visual RL; Dormant Ratio
  - ExpEnv: [DeepMind Control Suite](https://github.com/deepmind/dm_control),[Meta-world](https://github.com/rlworkgroup/metaworld),[Adroit](https://github.com/Farama-Foundation/D4RL)

- [Revisiting Data Augmentation in Deep Reinforcement Learning](https://openreview.net/pdf?id=EGQBpkIEuu)
  - Jianshu Hu, Yunpeng Jiang, Paul Weng
  - Keyword: Reinforcement Learning, Data Augmentation
  - ExpEnv: [DeepMind Control Suite](https://github.com/deepmind/dm_control)

- [Revisiting Plasticity in Visual Reinforcement Learning: Data, Modules and Training Stages](https://openreview.net/forum?id=0aR1s9YxoL)
  - Guozheng Ma, Lu Li, Sen Zhang, Zixuan Liu, Zhen Wang, Yixin Chen, Li Shen, Xueqian Wang, Dacheng Tao
  - Keyword: Plasticity, Visual Reinforcement Learning, Deep Reinforcement Learning, Sample Efficiency
  - ExpEnv: [DeepMind Control Suite](https://github.com/deepmind/dm_control),[Atari](https://github.com/openai/gym)

- [Entity-Centric Reinforcement Learning for Object Manipulation from Pixels](https://openreview.net/forum?id=uDxeSZ1wdI)
  - Dan Haramati, Tal Daniel, Aviv Tamar
  - Keyword: deep reinforcement learning, visual reinforcement learning, object-centric, robotic object manipulation, compositional generalization
  - ExpEnv: [IsaacGym](https://github.com/NVIDIA-Omniverse/IsaacGymEnvs)

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


## License

Awesome Multi-Modal Reinforcement Learning is released under the Apache 2.0 license.
