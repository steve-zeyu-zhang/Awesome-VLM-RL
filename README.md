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

- [Vision Language Models are In-Context Value Learners](https://openreview.net/forum?id=friHAl5ofG)  
  - Yecheng Jason Ma, Joey Hejna, Chuyuan Fu, Dhruv Shah, Jacky Liang, Zhuo Xu, Sean Kirmani, Peng Xu, Danny Driess, Ted Xiao, Osbert Bastani, Dinesh Jayaraman, Wenhao Yu, Tingnan Zhang, Dorsa Sadigh, Fei Xia  
  - Key: robot learning, vision-language model, value estimation, manipulation  
  - ExpEnv: more than 300 distinct real-world tasks across diverse robot platforms, including bimanual manipulation tasks

- [TopoNets: High performing vision and language models with brain-like topography](https://openreview.net/forum?id=THqWPzL00e)  
  - Mayukh Deb, Mainak Deb, Apurva Ratan Murty  
  - Key: topography, neuro-inspired, convolutional neural networks, Transformers, visual cortex, neuroscience  
  - ExpEnv: ResNet-18, ResNet-50, ViT, GPT-Neo-125M, NanoGPT

- [LOKI: A Comprehensive Synthetic Data Detection Benchmark using Large Multimodal Models](https://openreview.net/forum?id=z8sxoCYgmd)  
  - Junyan Ye, Baichuan Zhou, Zilong Huang, Junan Zhang, Tianyi Bai, Hengrui Kang, Jun He, Honglin Lin, Zihao Wang, Tong Wu, Zhizheng Wu, Yiping Chen, Dahua Lin, Conghui He, Weijia Li  
  - Key: LMMs, Deepfake, Multimodality  
  - ExpEnv: Video, Image, 3D, Text, Audio

- [Two Effects, One Trigger: On the Modality Gap, Object Bias, and Information Imbalance in Contrastive Vision-Language Models](https://openreview.net/forum?id=uAFHCZRmXk)  
  - Simon Schrodi, David T. Hoffmann, Max Argus, Volker Fischer, Thomas Brox  
  - Key: CLIP, modality gap, object bias, contrastive loss, data-centric, vision language models, VLM  
  - ExpEnv: Contrastive Vision-Language Models (VLMs) Analysis
  
- [Multi-Robot Motion Planning with Diffusion Models](https://openreview.net/forum?id=AUCYptvAf3)  
  - Yorai Shaoul, Itamar Mishani, Shivam Vats, Jiaoyang Li, Maxim Likhachev  
  - Key: Multi-Agent Planning, Robotics, Generative Models  
  - ExpEnv: Simulated logistics environments
  
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
