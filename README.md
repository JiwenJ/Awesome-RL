
<h1 align="center">Awesome RL</h1>

<div align="center">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![Static Badge](https://img.shields.io/badge/Status-Maintaining-%23ecfc03)
![Static Badge](https://img.shields.io/badge/PRs-Welcome-%23fc2003)
![Static Badge](https://img.shields.io/badge/License-MIT-%23e0ebdf)

</div>

A curated list of reinforcement learning resources, including books, courses, topics, repos, websites, communities, research groups, and modern RL directions such as offline RL, world models, RLHF, and agent RL.

> Note:
> - I keep the original structure of this repository as much as possible.
> - Legacy entries are preserved whenever possible, even if some are old.
> - Newer items are added into the existing structure instead of replacing it.

## Contents
- [Awesome RL](#awesome-rl)
   - [Books](#books)
   - [Courses](#courses)
   - [Research Topics](#rl-research-topics)
   - [GitHub Repo](#github-repo)
   - [Website](#website)
   - [Activity](#activity)
   - [Application](#application)
   - [Community](#community)
   - [Conference & Journal](#publish)
   - [Research Group](#research-group)
   - [Industry Group](#industry-group)
   - [Discussion](#discussion)
   - [Contributing](#contributing)
   - [Reference](#reference)

---

## Books
- English
   - Reinforcement Learning: An Introduction [[Book]](http://incompleteideas.net/book/ebook/the-book.html) [[Code]](http://incompleteideas.net/book/code/code.html) [Preferred] [[old version]](http://incompleteideas.net/book/bookdraft2017nov5.pdf) [[newest version]](http://incompleteideas.net/book/RLbook2020.pdf)
   - [Algorithm of Reinforcement Learning](https://github.com/borninfreedom/DeepLearning/blob/master/Books/Algorithms%20for%20Reinforcement%20Learning%20%E4%B9%A6%E7%B1%8D.pdf) [[Official]](https://sites.ualberta.ca/~szepesva/rlbook.html)
   - [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/)
   - [Reinforcement Learning for Sequential Decision and Optimal Control](https://link.springer.com/book/10.1007/978-981-19-7784-8)
   - [Dynamic programming and optimal control](https://web.mit.edu/dimitrib/www/DP2_Chapter%204_UPDATED.pdf)
   - Deep-Reinforcement-Learning-Hands-On [pdf 2 edition]
   - [Reinforcement Learning and Optimal Control](http://www.athenasc.com/rlbook_athena.html)
   - [Reinforcement Learning: Theory and Algorithms](https://rltheorybook.github.io/rltheorybook_AJKS.pdf)
   - Markov Decision Processes: Discrete Stochastic Dynamic Programming, by Martin Puterman.
   - Neuro-Dynamic Programming, by Dimitri Bertsekas and John Tsitsiklis.
   - [Multi-Agent Reinforcement Learning: Foundations and Modern Approaches](https://www.marl-book.com/)
   - [Safe Reinforcement Learning](https://www.cambridge.org/core/books/safe-reinforcement-learning/1E7F5627FC660E4C4ECAAA345B9A79F2)
   - [Probabilistic Machine Learning: Advanced Topics](https://probml.github.io/pml-book/book2.html)  (useful for model-based RL and sequential decision making)
- Chinese
   - [动手学强化学习](https://hrl.boyuai.com/) 张伟楠
   - 深度强化学习落地指南 魏宁
   - 深度强化学习 王树森 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%BA%A6%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%20Deep%20Reinforcement%20Learning%20(%E7%8E%8B%E6%A0%91%E6%A3%AE%20%E9%BB%8E%E5%BD%A7%E5%90%9B%20%E5%BC%A0%E5%BF%97%E5%8D%8E).pdf)
   - [EasyRL 强化学习教程](https://github.com/datawhalechina/easy-rl)
   - 强化学习实战: 强化学习在阿里的技术演进和业务创新 笪庆 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%AE%9E%E6%88%98%EF%BC%9A%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%9C%A8%E9%98%BF%E9%87%8C%E7%9A%84%E6%8A%80%E6%9C%AF%E6%BC%94%E8%BF%9B%E5%92%8C%E4%B8%9A%E5%8A%A1%E5%88%9B%E6%96%B0%20(%E7%AC%AA%E5%BA%86%EF%BC%8C%E6%9B%BE%E5%AE%89%E7%A5%A5).pdf)
   - 深度强化学习 董豪 [[PDF]](https://deepreinforcementlearningbook.org/)
   - 深入浅出强化学习 郭宪 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%85%A5%E6%B5%85%E5%87%BA%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%9A%E5%8E%9F%E7%90%86%E5%85%A5%E9%97%A8-%E9%83%AD%E5%AE%AA-%E6%96%B9%E5%8B%87%E7%BA%AF.pdf)
   - [神经网络与深度学习](https://nndl.github.io/) 邱锡鹏 [[PDF]](https://nndl.github.io/nndl-book.pdf)
   - 机器学习 周志华 [[PDF]]()
   - 统计强化学习: 现代机器学习方法 杉山将 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E7%BB%9F%E8%AE%A1%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%9A%E7%8E%B0%E4%BB%A3%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95-%E6%9D%89%E5%B1%B1%E5%B0%86.pdf)
   - 深度强化学习核心算法与应用 陈世勇 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%BA%A6%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E6%A0%B8%E5%BF%83%E7%AE%97%E6%B3%95%E4%B8%8E%E5%BA%94%E7%94%A8-(%E9%99%88%E4%B8%96%E5%8B%87-%E8%8B%8F%E5%8D%9A%E8%A7%88-%E6%9D%A8%E6%95%AC%E6%96%87).pdf)
   - 深度强化学习边做边学 小川雄太郎 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%BA%A6%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E8%BE%B9%E5%81%9A%E8%BE%B9%E5%AD%A6%20(%E5%B0%8F%E5%B7%9D%E9%9B%84%E5%A4%AA%E9%83%8E(Yutaro%20Ogawa)%E8%91%97%20%E7%94%B3%E5%AF%8C%E9%A5%B6%E4%BA%8E%E5%83%A1%E8%AF%91).pdf)
   - 强化学习 邹伟 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%20(%E9%82%B9%E4%BC%9F%2C%20%E9%AC%B2%E7%8E%B2%2C%20%E5%88%98%E6%98%B1%E6%9D%93).pdf)
   - 强化学习精要: 核心算法与TensorFlow实现 冯超 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E7%B2%BE%E8%A6%81%20%E6%A0%B8%E5%BF%83%E7%AE%97%E6%B3%95%E4%B8%8ETensorFlow%E5%AE%9E%E7%8E%B0%20(%E5%86%AF%E8%B6%85).pdf)
   - 强化学习入门: 从原理到实践 叶强 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%85%A5%E9%97%A8%EF%BC%9A%E4%BB%8E%E5%8E%9F%E7%90%86%E5%88%B0%E5%AE%9E%E8%B7%B5%20(%E5%8F%B6%E5%BC%BA%20%20%E9%97%AB%E7%BB%B4%E6%96%B0%20%20%E9%BB%8E%E6%96%8C).pdf)
   - 强化学习与决策控制相关中文教材（待补充）

   *note: 作者均只列举第一人*

---
## Courses
- UCL. [Reinforcement Learning](https://www.davidsilver.uk/teaching/). [David Silver](https://www.davidsilver.uk/). Difficulty: [&#9733;]
- UCL. [Advanced Topics](https://github.com/Zhenye-Na/advanced-deep-learning-and-reinforcement-learning-deepmind). [David Silver](https://www.davidsilver.uk/).
- Tencent. [Reinforcement Learning](https://mofanpy.com/tutorials/machine-learning/reinforcement-learning/). MoFan. Difficulty: [&#9733;]
- National Taiwan University. [DRL](https://www.bilibili.com/video/av24724071/?p=1&vd_source=2026817085b0497e7510e8a952dac21e). [Hung-Yi LEE](https://speech.ee.ntu.edu.tw/~hylee/index.php). [Preferred]. Difficulty: [&#9733;]
- Deep Reinforcement Learning. Shusen Wang. [[Bilibili]](https://www.bilibili.com/video/BV12o4y197US/?spm_id_from=333.337.search-card.all.click&vd_source=1b5a680450b015abb52a712f2dbac81a)
- UCLA. [Intro to Reinforcement Learning](https://www.youtube.com/watch?v=IkEF4LpH5Ys&list=PLySQw_vQ73PyDY68KF0HdCzcILBoHVTvD). [Bolei Zhou](https://boleizhou.github.io/). Difficulty: [&#9733;]
- UC Berkeley CS294 (before), CS285 Sergey Levine
- Stanford CS234 RL Emma Brunskill [[Bilibili]](https://www.bilibili.com/video/BV1sb411s7eQ/?from=search&seid=14467709922277911537&spm_id_from=333.337.0.0&vd_source=1b5a680450b015abb52a712f2dbac81a) [[Official]](http://web.stanford.edu/class/cs234/)
- [MIT RL Dimitri Bertsekas](http://www.mit.edu/~dimitrib/RLbook.html)
- RL and control THU
- CMU Deep Reinforcement Learning Katerina Fragkiadaki [[Link]](https://cmudeeprl.github.io/403website_s23/)
- Udacity
- Lex Fridman
- [ETHz Dynamic Programming and Optimal Control Raffaello D'Andrea](https://idsc.ethz.ch/education/lectures/optimal-control.html)
- [Pieter Abbeel](https://people.eecs.berkeley.edu/~pabbeel/)
- [高级机器学习 唐杰](https://www.aminer.cn/aml)
- 李升波
- UIUC, [CS 542](http://nanjiang.cs.illinois.edu/cs542/), [CS 443](http://nanjiang.cs.illinois.edu/cs443/), Nan Jiang.
- R. Srikant. UIUC ECE 586.
- Ron Parr. Duke CompSci 590.2.
- Ben Van Roy. Stanford MS&E 338.
- Ambuj Tewari and Susan Murphy. U Michigan STATS 710.
- Susan Murphy. Harvard Stat 234.
- Alekh Agarwal and Alex Slivkins. Columbia COMS E6998.001.
- Daniel Russo. Columbia B9140-001.
- Shipra Agrawal. Columbia IEOR 8100.
- Emma Brunskill CMU 15-889e.
- Philip Thomas. U Mass CMPSCI 687.
- Michael Littman. Brown CSCI2951-F.
- NJU. [IntroRL](http://www.lamda.nju.edu.cn/introRL/). [Yang Yu](https://www.wolai.com/eyounx/dtR1MTyRXS5tP5Cex4KtdK).
- CMU 16 745
- CSE 691 asu
- UCLA, [Reinforcement Learning of Large Language Models, Spring 2025](https://ernestryu.com/courses/RL-LLM.html) Ernest K. Ryu
- [Berkeley CS285 Deep RL](http://rail.eecs.berkeley.edu/deeprlcourse/)
- [OpenAI Spinning Up Education](https://spinningup.openai.com/en/latest/)

---
## RL Research Topics
- ### Approximate Dynamic Programming and Offline RL
   > Approximate Dynamic Programming (ADP) concerns obtaining approximate solutions to large planning problems, often with the help of sampling and function approximation. Many ADP methods can be considered as prototype algorithms for popular value-based RL algorithms used today, especially in the offline setting, so it is important to understand their behaviors and guarantees.
  - #### Online + Offline (Hybrid)
    - Policy Finetuning: Bridging Sample-Efficient Offline and Online Reinforcement Learning
    - Policy Finetuning in Reinforcement Learning via Design of Experiments using Offline Data
    - Hybrid rl: Using both offline and online data can make rl efficient
  - #### Offline RL
    - Batch-constrained learning / support constraint
    - Conservative value learning
    - Sequence modeling for decision making
    - Off-policy evaluation and selection under dataset shift
- ### Multi-agent RL
  - Cooperative MARL
  - Mixed cooperative-competitive learning
  - Value decomposition and factorization
  - Emergent communication and social learning
  - Population-based training and league systems
- ### Off-policy Evaluation
  > How to estimate the performance of a policy using data collected from a different policy? This question has important implications in safety and real-world applications of RL.
- ### Model-based RL / World Models
  - Latent dynamics modeling
  - Planning with learned models
  - PETS / MBPO / Dreamer / MuZero / TD-MPC line
  - Simulators, control, and long-horizon rollout stability
- ### Policy Optimization
  - Policy gradient / actor-critic
  - PPO / TRPO / natural policy gradient
  - Entropy regularization and trust region methods
  - Credit assignment and variance reduction
- ### Distributional RL
  - Return distribution modeling
  - Risk-sensitive RL
  - Quantile-based value estimation
- ### Safe RL / Constrained RL
  - Constraint satisfaction under uncertainty
  - Shielding, recovery, and risk control
  - Safe exploration
- ### Hierarchical RL
  - Options framework
  - Skill discovery
  - Temporal abstraction
- ### Exploration
  - Intrinsic motivation
  - Curiosity-driven exploration
  - Count-based and uncertainty-aware methods
- ### RL for Robotics and Control
  - Locomotion and manipulation
  - Sim2real
  - MPC + RL
  - Industrial control and autonomous driving
- ### RL for Recommender Systems / Ads / Operations Research
  - Long-term user value
  - Slate recommendation
  - Dynamic pricing, scheduling, routing, resource allocation
- ### RLHF / Post-training / Agent RL
  - RLHF / RLAIF / constitutional preferences
  - DPO / IPO / ORPO / preference optimization family
  - Verifier-based RL
  - Code, math, reasoning, and tool-use RL
  - Web agents, environment interaction, and long-horizon agent training
- ### RL Theory
  - Sample complexity
  - Regret minimization
  - Bellman rank, function approximation, and generalization
  - Partial observability and identifiability

---
## GitHub Repo
- [rlcode](https://github.com/rlcode/reinforcement-learning)
- [Deep-Reinforcement-Learning-Algorithms-with-PyTorch](https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch)
- [Deep-reinforcement-learning-with-pytorch](https://github.com/AndyYue1893/Deep-reinforcement-learning-with-pytorch)
- [reinforcement-learning [most stars]](https://github.com/dennybritz/reinforcement-learning)
- [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3)
- [Google Dopamine](https://github.com/google/dopamine)
- [Intel Coach](https://github.com/IntelLabs/coach)
- [CleanRL](https://github.com/vwxyzjn/cleanrl)
- [RLlib](https://github.com/ray-project/ray)
- [Acme](https://github.com/google-deepmind/acme)
- [Tianshou](https://github.com/thu-ml/tianshou)
- [DI-engine](https://github.com/opendilab/DI-engine)
- [PettingZoo](https://github.com/Farama-Foundation/PettingZoo)
- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium)
- [D4RL](https://github.com/Farama-Foundation/D4RL)
- [PyMARL](https://github.com/oxwhirl/pymarl)
- [MARLlib](https://github.com/Replicable-MARL/MARLlib)
- [Sample Factory](https://github.com/alex-petrenko/sample-factory)
- [TRL](https://github.com/huggingface/trl)
- [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF)
- [verl](https://github.com/volcengine/verl)
- [Mujoco](https://github.com/google-deepmind/mujoco)
- [robosuite](https://github.com/ARISE-Initiative/robosuite)
- [ManiSkill](https://github.com/haosulab/ManiSkill)

---

## Website
- [PaperWithCode](https://paperswithcode.com/search?q_meta=&q_type=&q=reinforcement+learning)
- [从零开始推导贝尔曼方程](https://www.bilibili.com/video/BV1fN41197ES/?spm_id_from=333.337.search-card.all.click)
- [强化学习知识大讲堂 郭宪](https://zhuanlan.zhihu.com/sharerl)
- [智能单元](https://zhuanlan.zhihu.com/intelligentunit)
- [神经网络与强化学习](https://zhuanlan.zhihu.com/c_101836530)
- [强化学习基础David Silver笔记 陈雄辉](https://zhuanlan.zhihu.com/c_135909947)
- [博客园 刘建平](https://www.cnblogs.com/pinard/)
- [Farama Foundation](https://farama.org/)
- [OpenDILab](https://opendilab.net/)
- [Lilian Weng Blog](https://lilianweng.github.io/)
- [Spinning Up](https://spinningup.openai.com/en/latest/)
- [AI Alignment Forum](https://www.alignmentforum.org/)
- [BAIR Blog](https://bair.berkeley.edu/blog/)

---
## Activity
- [Tencent AIArena](https://aiarena.tencent.com/aiarena/zh)
- AWS DeepRacer
- [MineRL Competition](https://www.minerl.io/)
- [NetHack Challenge](https://nethackchallenge.com/)
- Kaggle / KDD / RecSys related sequential decision competitions

---
## Application
- [Quant](./doc/RL4Quant.md)
- [Gaming](./doc/RL4Gaming.md)
- [Optimization](./doc/RL4OPT.md)
- [Recommendation](./doc/RL4Rem.md)
- [LLMs](./doc/LLM4RL.md)
- [Distribution](./doc/DistributedRL.md)
- Robotics
- Autonomous Driving
- Recommender System / Ads
- Operations Research
- Alignment / Agent / Tool Use
---
## Community
* [RLChina](http://rlchina.org/)
* [DeepRLHub](http://www.deeprlhub.com/)
* [智源社区](https://hub.baai.ac.cn/)
* [上海AILAB-浦策](https://opendilab.net/home)
* [Farama Community](https://farama.org/)
* [OpenDILab](https://opendilab.net/)

---
## <div id="publish">Conference & Journal</div>

Conference: NIPS, ICML, ICLR, AAAI, IJCAI, AAMAS, IROS, CoRL, RSS, etc.

Journal: JMLR, JAIR, JAAMAS, TMLR, etc.

---

## Research Group
* [Asia]()
   * [CASIA]()
     * Haifeng Zhang [[Homepage]](https://pkuzhf.github.io/) [[Group]](http://marl.ia.ac.cn/)
     * Zhiqiang Pu [[Homepage]](https://people.ucas.edu.cn/~pzq)
     * Dongbin Zhao [[Homepage]](https://people.ucas.ac.cn/~zhaodongbin)
     * Junliang Xing [[Homepage]](https://people.ucas.ac.cn/~jlxing)
   * [NJU]()
     * Yang Yu - Interested in [[Homepage]](https://jxwuyi.weebly.com/)
     * Yinghuan Shi [[Homepage]](https://cs.nju.edu.cn/shiyh/index.htm)
     * Yang Gao [[Homepage]](https://cs.nju.edu.cn/gaoyang/index.htm)
     * Zongzhang Zhang [[Homepage]](https://ai.nju.edu.cn/zhangzongzhang/index.htm)
     * NJU SME Faculty
   * [SJTU]()
      * Yong Yu [[Homepage]](https://apex.sjtu.edu.cn/members/yyu)
      * Weinan Zhang [[Homepage]](http://wnzhang.net/)
      * Kai Yu [[Homepage]](https://x-lance.sjtu.edu.cn/en/members/kai_yu)
      * Ying Wen [[Homepage]](https://yingwen.io/)
   * [PKU]()
      * Yaodong Yang [[Homepage]](https://www.yangyaodong.com/)
      * Zhihua Zhang [[Homepage]](https://www.math.pku.edu.cn/teachers/zhzhang/)
      * Zongqing Lu [[Homepage]](https://z0ngqing.github.io/)
      * Hao Dong [[Homepage]](https://zsdonghao.github.io/)
   * [THU]()
      * Chongjie Zhang [[Homepage]](http://people.iiis.tsinghua.edu.cn/~zhang/)
      * Yi Wu [[Homepage]](https://jxwuyi.weebly.com/) [[Group]](https://jxwuyi.weebly.com/)
      * Zhihua Zhang [[Homepage]](https://www.math.pku.edu.cn/teachers/zhzhang/)
      * Shengbo Li [[Homepage]](http://www.idlab-tsinghua.com/thulab/labweb/dpeople.html?11) [[Group]](http://www.idlab-tsinghua.com/thulab/labweb/index.html)
   * [USTC]()
      * Feng Wu [[Homepage]](http://staff.ustc.edu.cn/~wufeng02/index.html?lang=zh)
      * Houqiang Li [[Homepage]](http://staff.ustc.edu.cn/~lihq/)
   * [CUHK-SZ]()
      * Baoxiang Wang [[Homepage]](https://bxiangwang.github.io/)
      * Hongyuan Zha [[Homepage]](https://sds.cuhk.edu.cn/en/teacher/65)
   * [CUHK]()
      * Baoxiang Wang
   * [TJU]()
      * Jianye Hao [[Homepage]](https://jxwuyi.weebly.com/) [[Group]](https://jxwuyi.weebly.com/)
   * [SIAT]()
     * Yunduan Cui [[Homepage]](https://cuiyunduan.vercel.app/zh/)
   * [HIT-SZ]()
     * Yanjie Li [[Homepage]](http://faculty.hitsz.edu.cn/liyanjie)
   * [NTU]()
     * Bo An [[Homepage]](https://personal.ntu.edu.sg/boan/index.html)
   * [NUDT]()
     * Xin Xv
   * [SYSU]()
     * Chao Yu [[Homepage]](https://cse.sysu.edu.cn/content/4883)
* [North America]()
   * [Mcgill]()
     * Doina Precup
     * Joelle Pineau
   * [Alberta]()
     * Michael Bowling [[Homepage]]()
   * [UCLA]()
      * Bolei Zhou  [[Homepage]](https://boleizhou.github.io/)
   * [MIT]()
     * Pulkit Agrawal
     * Leslie Kaelbling
     * Russ Tedrake
     * Nicholas Roy
   * [CMU]()
     * Geoffrey Gordon
     * Emma Brunskill
     * Jeff Schneider
     * Andrew Moore
     * Jessica K. Hodgins
     * Wen Sun [[Homepage]](https://wensun.github.io/)
   * [Berkeley]()
     *  Sergey Levine
     *  Michael Jordan
     *  Pieter Abbeel [[Gruop]](https://bair.berkeley.edu/index.html#header)
     *  Dimitri Bertsekas
     *  Emma Brunskill
     *  Chelsea Finn
     *  Anca Dragan
     *  Ken Goldberg
     *  Stuart Russell
   * [Standford]()
     * Benjamin Van Roy
     * Emma Brunskill
     * Mykel Kochenderfer
     * Dorsa Sadigh
     * Tengyu Ma
     * Chelsea Finn
     * Andrew Ng
   * [UIUC]()
     * Nan Jiang [Homepage](https://nanjiang.cs.illinois.edu/)
   * [Duke]()
     * Ronald Parr [[Homepage]](https://users.cs.duke.edu/~parr/)
   * [Brown]()
     * Michael Littman
   * [Columbia]()
     * Daniel Russo
     * Shipra Agrawal
     * Alekh Agarwal
     * Alex Slivkins
   * [Toronto]()
     * Jimmy Ba [[Homepage]](https://jimmylba.github.io/)
     * Sheila McIlraith [[Homepage]](https://www.cs.toronto.edu/~sheila/)
* [Europe]()
   * [INRIA]()
     * Flower Team [[Homepage]](https://flowers.inria.fr/)
   * [ETH Zurich]()
     * Andreas Krause [[Homepage]](https://las.inf.ethz.ch/krausea)
   * [Oxford]()
     * Jakob Foerster
   * [Cambridge]()
   * [IC]()
   * [UCL]()
     * [Jun Wang]()
     * [David Silver](https://www.davidsilver.uk/)

#### Other outer link
- [Awesome-CV-Team](https://github.com/extreme-assistant/Awesome-CV-Team)


**[⬆ back to top](#contents)**
  
---

## Industry Group
* [China]()
   * [BaiDu]()
      * [PARL]()
   * [Tencent]()
   * [NetEase]()
   * [ByteDance]()
   * [Di Di]()
   * [BaiDu]()
   * [MSRA]()
   * [Huawei]()
   * [PINGAN]()
   * [Polixir.ai]()
   * [Inspirai]()
   * [Horizon]()
   * [Momenta]()
   * [Parametrix.ai]()
   * [Alibaba]()
   * [Kwai]()
* [Oversea]()
  * OpenAI
  * DeepMind
  * Google Brain
  * FAIR
  * Salesforce Research
 
**[⬆ back to top](#contents)**

---
## Misc
- [Useful inequalities cheat sheet](http://www.lkozma.net/inequalities_cheat_sheet/)
- [Concentration of measure](https://www.stat.cmu.edu/~larry/=sml/Concentration.pdf)
- [dalmia/David-Silver-Reinforcement-learning: Notes for the Reinforcement Learning course by David Silver along with implementation of various algorithms. (github.com)](https://github.com/dalmia/David-Silver-Reinforcement-learning)
- [强化学习路线推荐及资料整理 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/344196096)
- [PacktPublishing/Mastering-Reinforcement-Learning-with-Python: Mastering Reinforcement Learning with Python, published by Packt (github.com)](https://github.com/PacktPublishing/Mastering-Reinforcement-Learning-with-Python)
- [Farama Docs](https://farama.org/)
- [BAIR Blog](https://bair.berkeley.edu/blog/)

**[⬆ back to top](#contents)**

---
## Discussion
1. Policy-based vs. Value-based [[ZhiHu]](https://www.zhihu.com/question/316626294/answer/627373838)
2. [Philosophy of Reinforcement Learning](./doc/RL_Philosophy.md)
3. Offline RL vs. Online RL vs. Hybrid RL
4. World Models vs. Model-Free RL
5. RLHF / Preference Optimization / Agent RL


**[⬆ back to top](#contents)**

---
## Contributing

This is an active repository and it is time-consuming to maintain the content. **So your contributions really matter!**

If you find it helpful, please vote for it by adding 👍.

If you have any question about this list, do not hesitate to contact me at 1546631808@qq.com.

Preferred ways to contribute:
- preserve the existing structure and add missing resources;
- fix broken links;
- add newer official references for old entries;
- expand topic pages under `./doc/`.

**[⬆ back to top](#contents)**

---

## Reference
* https://www.zhihu.com/collection/840642960
* https://www.zhihu.com/question/516672871
* http://www.deeprlhub.com/d/154/2
* https://zhuanlan.zhihu.com/p/571011569
* [东栏雪](https://www.zhihu.com/question/277325426/answer/2712724382)

**[⬆ back to top](#contents)**

