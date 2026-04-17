<h1 align="center">Awesome RL</h1>

<div align="center">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![Status](https://img.shields.io/badge/Status-Maintained-brightgreen)
![PRs](https://img.shields.io/badge/PRs-Welcome-red)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

</div>

A curated list of reinforcement learning resources, covering foundations, theory, algorithms, benchmarks, toolkits, applications, and modern RL for LLMs and agents.

This repository aims to be a **high-signal entry point** rather than an unstructured link dump:
- prefer official links when possible;
- prioritize resources that are still useful for study or research;
- cover both **classic RL** and **modern post-training / agent RL** directions.

---

## Contents
- [How to use this repo](#how-to-use-this-repo)
- [Learning roadmap](#learning-roadmap)
- [Books](#books)
- [Courses](#courses)
- [Surveys and reading lists](#surveys-and-reading-lists)
- [Canonical papers by topic](#canonical-papers-by-topic)
- [Libraries and frameworks](#libraries-and-frameworks)
- [Environments, benchmarks, and datasets](#environments-benchmarks-and-datasets)
- [Applications](#applications)
- [Websites and communities](#websites-and-communities)
- [Conferences and journals](#conferences-and-journals)
- [Selected research groups](#selected-research-groups)
- [Contributing](#contributing)
- [Reference](#reference)

---

## How to use this repo

Different readers usually need different entry points:

- **Beginner**
  - Start with Sutton & Barto + David Silver.
  - Then learn DQN, policy gradient, actor-critic, PPO, SAC.
  - After that, move to offline RL / model-based RL / multi-agent RL.

- **Research student**
  - Build a clean map of the field first: foundations, theory, benchmarks, classical papers.
  - Then pick one line: offline RL, MBRL, MARL, safe RL, RLHF, agent RL, robotics, recommender systems.

- **Engineer / practitioner**
  - Focus on libraries, reproducible baselines, benchmarks, evaluation, and deployment constraints.
  - For LLM post-training, pay special attention to reward design, data quality, rollout system design, and verifier-based training.

---

## Learning roadmap

### Stage 0. Prerequisites
- Linear algebra, probability, optimization
- Markov chains / Markov decision processes (MDP)
- Basic deep learning and supervised learning

### Stage 1. Tabular RL and fundamentals
- Bandits
- Dynamic programming
- Monte Carlo methods
- TD learning
- Q-learning / SARSA
- Exploration vs. exploitation

Recommended:
- Sutton & Barto
- David Silver's RL course

### Stage 2. Deep RL basics
- DQN family
- Policy gradient
- Actor-critic
- PPO / A2C / A3C
- Continuous control: DDPG / TD3 / SAC

Recommended:
- Spinning Up
- CS285 / CS234
- CleanRL / Stable-Baselines3

### Stage 3. Major modern directions
- Model-based RL and world models
- Offline RL
- Multi-agent RL
- Safe RL / constrained RL
- Hierarchical RL
- Distributional RL
- RL for robotics and control

### Stage 4. RL for foundation models and agents
- RLHF / RLAIF
- Preference learning and ranking losses
- Verifier-based RL
- Tool-use and agent trajectories
- Test-time planning, long-horizon credit assignment, environment interaction

---

## Books

### Foundations
- [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html) — Richard S. Sutton, Andrew G. Barto. The default starting point.
- [Algorithms for Reinforcement Learning](https://sites.ualberta.ca/~szepesva/rlbook.html) — Csaba Szepesvári. Concise and theory-friendly.
- [Dynamic Programming and Optimal Control](http://www.mit.edu/~dimitrib/dpbook.html) — Dimitri P. Bertsekas. Classic control / DP perspective.
- [Reinforcement Learning and Optimal Control](http://www.athenasc.com/rlbook_athena.html) — Dimitri P. Bertsekas. Strong bridge between RL and control.
- [Reinforcement Learning: Theory and Algorithms](https://rltheorybook.github.io/) — Alekh Agarwal, Nan Jiang, Sham Kakade, Wen Sun. Modern theory-oriented reference.
- [Reinforcement Learning for Sequential Decision and Optimal Control](https://link.springer.com/book/10.1007/978-981-19-7784-8) — Shengbo Eben Li, et al.

### Multi-agent RL
- [Multi-Agent Reinforcement Learning: Foundations and Modern Approaches](https://www.marl-book.com/) — the most useful modern entry point for MARL.

### Practice and engineering
- [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/) — not a book, but still one of the best practical intros.
- [Deep Reinforcement Learning Hands-On](https://www.packtpub.com/en-us/product/deep-reinforcement-learning-hands-on-9781804611211) — practical deep RL implementation-oriented book.

### Chinese resources
- [动手学强化学习](https://hrl.boyuai.com/)
- [EasyRL 强化学习教程](https://github.com/datawhalechina/easy-rl)
- [神经网络与深度学习](https://nndl.github.io/) — 邱锡鹏

> Note: this README now prefers official or open links. For copyrighted books without official free versions, link to the official page instead of unofficial PDF mirrors.

---

## Courses

### Core RL
- [UCL Reinforcement Learning](https://www.davidsilver.uk/teaching/) — David Silver
- [UC Berkeley CS285: Deep Reinforcement Learning](http://rail.eecs.berkeley.edu/deeprlcourse/)
- [Stanford CS234: Reinforcement Learning](https://web.stanford.edu/class/cs234/)
- [MIT Reinforcement Learning and Optimal Control](http://www.mit.edu/~dimitrib/RLbook.html) — Dimitri Bertsekas
- [UCLA Intro to Reinforcement Learning](https://www.youtube.com/playlist?list=PLySQw_vQ73PyDY68KF0HdCzcILBoHVTvD) — Bolei Zhou
- [CMU Deep Reinforcement Learning](https://cmudeeprl.github.io/)
- [NJU IntroRL](http://www.lamda.nju.edu.cn/introRL/) — Yang Yu / LAMDA
- [UIUC RL courses](https://nanjiang.cs.illinois.edu/) — Nan Jiang

### RL for LLMs / foundation models
- [Reinforcement Learning of Large Language Models](https://ernestryu.com/courses/RL-LLM.html) — a useful bridge from classical RL to modern post-training.

---

## Surveys and reading lists

### General reading lists
- [Papers with Code: Reinforcement Learning](https://paperswithcode.com/task/reinforcement-learning)
- [Farama Foundation](https://farama.org/)
- [OpenDILab](https://opendilab.net/)
- [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/)

### Topic-specific surveys and overviews
- [Safe Reinforcement Learning: A Survey](https://jmlr.org/papers/v16/garcia15a.html)
- [A Survey of Offline Reinforcement Learning](https://arxiv.org/abs/2203.01387)
- [Model-Based Reinforcement Learning: A Survey](https://arxiv.org/abs/2006.16712)
- [A Survey and Critique of Multiagent Deep Reinforcement Learning](https://arxiv.org/abs/1810.05587)
- [Deep Reinforcement Learning: An Overview](https://arxiv.org/abs/1701.07274)

### Useful blogs / notes
- [Lilian Weng's blog](https://lilianweng.github.io/) — especially useful for policy optimization, reward learning, agents, and LLM/RL topics.
- [David Silver course notes and videos](https://www.davidsilver.uk/teaching/)

---

## Canonical papers by topic

This section is intentionally **representative instead of exhaustive**. It is designed to help readers build the map of the field quickly.

### 1. Foundations
- [Q-Learning](https://link.springer.com/article/10.1007/BF00992698) — Watkins & Dayan, 1992
- [Policy Gradient Methods for Reinforcement Learning with Function Approximation](https://proceedings.neurips.cc/paper/1999/hash/464d828b85b0bed98e80ade0a5c43b0f-Abstract.html) — Sutton et al., 1999

### 2. Value-based deep RL
- [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602) — DQN
- [Human-level control through deep reinforcement learning](https://www.nature.com/articles/nature14236) — Nature DQN paper
- [Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/abs/1509.06461)
- [Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/abs/1511.06581)
- [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)
- [Rainbow: Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/abs/1710.02298)
- [A Distributional Perspective on Reinforcement Learning](https://arxiv.org/abs/1707.06887) — C51

### 3. Policy gradient and actor-critic
- [Trust Region Policy Optimization](https://arxiv.org/abs/1502.05477) — TRPO
- [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783) — A3C
- [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347) — PPO
- [Deterministic Policy Gradient Algorithms](https://proceedings.mlr.press/v32/silver14.html)
- [Continuous Control with Deep Reinforcement Learning](https://arxiv.org/abs/1509.02971) — DDPG
- [Addressing Function Approximation Error in Actor-Critic Methods](https://arxiv.org/abs/1802.09477) — TD3
- [Soft Actor-Critic](https://arxiv.org/abs/1801.01290) — SAC

### 4. Planning, search, and self-play
- [Mastering the game of Go with deep neural networks and tree search](https://www.nature.com/articles/nature16961) — AlphaGo
- [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm](https://arxiv.org/abs/1712.01815) — AlphaZero
- [Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model](https://arxiv.org/abs/1911.08265) — MuZero

### 5. Model-based RL and world models
- [Deep Planning Network](https://arxiv.org/abs/1708.04782)
- [PETS: Deep Reinforcement Learning in a Handful of Trials using Probabilistic Dynamics Models](https://arxiv.org/abs/1805.12114)
- [MBPO: Model-Based Policy Optimization](https://arxiv.org/abs/1906.08253)
- [Dream to Control: Learning Behaviors by Latent Imagination](https://arxiv.org/abs/1912.01603) — Dreamer
- [Mastering Diverse Domains through World Models](https://arxiv.org/abs/2301.04104) — DreamerV3
- [TD-MPC](https://arxiv.org/abs/2203.04955)
- [TD-MPC2](https://arxiv.org/abs/2310.16828)

### 6. Offline RL
- [Off-Policy Deep Reinforcement Learning without Exploration](https://arxiv.org/abs/1812.02900) — BCQ
- [Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://arxiv.org/abs/1906.00949) — BEAR
- [Conservative Q-Learning for Offline Reinforcement Learning](https://arxiv.org/abs/2006.04779) — CQL
- [Offline Reinforcement Learning with Implicit Q-Learning](https://arxiv.org/abs/2110.06169) — IQL
- [Decision Transformer: Reinforcement Learning via Sequence Modeling](https://arxiv.org/abs/2106.01345)

### 7. Multi-agent RL
- [Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments](https://arxiv.org/abs/1706.02275) — MADDPG
- [Counterfactual Multi-Agent Policy Gradients](https://arxiv.org/abs/1705.08926) — COMA
- [Value-Decomposition Networks For Cooperative Multi-Agent Learning](https://arxiv.org/abs/1706.05296) — VDN
- [QMIX: Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1803.11485)
- [The Surprising Effectiveness of PPO in Cooperative Multi-Agent Games](https://arxiv.org/abs/2103.01955) — MAPPO

### 8. RL for language models, preference learning, and agents
- [Learning to summarize from human feedback](https://arxiv.org/abs/2009.01325)
- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) — InstructGPT / RLHF milestone
- [Direct Preference Optimization](https://arxiv.org/abs/2305.18290) — not RL, but essential for comparison in post-training pipelines
- [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300) — representative GRPO-style post-training direction

### 9. Additional important themes worth studying
- Distributional RL
- Hierarchical RL
- Safe / constrained RL
- Exploration and intrinsic motivation
- Sim2Real and robotics RL
- RL for recommender systems
- RL for alignment, agents, tool use, and verifiable domains

---

## Libraries and frameworks

### General-purpose RL
- [Stable-Baselines3](https://stable-baselines3.readthedocs.io/)
- [CleanRL](https://github.com/vwxyzjn/cleanrl)
- [RLlib](https://docs.ray.io/en/latest/rllib/)
- [Acme](https://github.com/google-deepmind/acme)
- [Dopamine](https://github.com/google/dopamine)
- [Tianshou](https://github.com/thu-ml/tianshou)
- [DI-engine](https://github.com/opendilab/DI-engine)
- [Sample Factory](https://github.com/alex-petrenko/sample-factory)

### Multi-agent RL
- [PettingZoo](https://pettingzoo.farama.org/)
- [MARLlib](https://github.com/Replicable-MARL/MARLlib)
- [PyMARL](https://github.com/oxwhirl/pymarl)

### RL for LLM post-training
- [TRL](https://github.com/huggingface/trl)
- [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF)
- [verl](https://github.com/volcengine/verl)

### Reproducibility / reference repositories
- [rlcode](https://github.com/rlcode/reinforcement-learning)
- [dennybritz/reinforcement-learning](https://github.com/dennybritz/reinforcement-learning)
- [p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch](https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch)
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)

---

## Environments, benchmarks, and datasets

### Classic control and Atari
- [Gymnasium](https://gymnasium.farama.org/)
- [Arcade Learning Environment (ALE)](https://ale.farama.org/)
- [MinAtar](https://github.com/kenjyoung/MinAtar)
- [Procgen](https://github.com/openai/procgen)

### Continuous control and robotics
- [MuJoCo](https://mujoco.org/)
- [DeepMind Control Suite](https://github.com/google-deepmind/dm_control)
- [Meta-World](https://meta-world.github.io/)
- [robosuite](https://robosuite.ai/)
- [ManiSkill](https://www.maniskill.ai/)
- [Brax](https://github.com/google/brax)

### Multi-agent environments
- [PettingZoo](https://pettingzoo.farama.org/)
- [SMAC](https://github.com/oxwhirl/smac)
- [MPE / MPE2](https://pettingzoo.farama.org/environments/mpe/)

### Offline RL datasets
- [D4RL](https://github.com/Farama-Foundation/D4RL)
- [RL Unplugged](https://arxiv.org/abs/2006.13888)
- [MineRL](https://minerl.readthedocs.io/)

### Evaluation reminders
When reading RL papers or running experiments, always keep these in mind:
- environment versions matter;
- normalized score definitions matter;
- number of seeds matters;
- online vs. offline setting should never be mixed casually;
- wall-clock efficiency and system complexity often matter as much as sample efficiency.

---

## Applications

This repository already contains several subpages under [`./doc`](./doc), which are good starting anchors and can be expanded further:
- [Quant](./doc/RL4Quant.md)
- [Gaming](./doc/RL4Gaming.md)
- [Optimization](./doc/RL4OPT.md)
- [Recommendation](./doc/RL4Rem.md)
- [LLMs](./doc/LLM4RL.md)
- [Distributed RL](./doc/DistributedRL.md)

### Representative application directions
- **Games**: Atari, Go, Chess, StarCraft, Dota
- **Robotics and control**: locomotion, manipulation, autonomous driving, industrial control
- **Recommendation / ads / ranking**: long-term user value, slate recommendation, bandits + RL
- **Operations research / optimization**: routing, scheduling, resource allocation, combinatorial optimization
- **Finance / quant**: portfolio allocation, execution, market making, decision under uncertainty
- **LLMs and agents**: RLHF, tool use, web agents, code / math post-training, verifier-based optimization

### Notes by application
- **Recommendation systems** usually require strong off-policy evaluation and careful reward design.
- **Robotics** usually requires simulation quality, domain randomization, or offline data.
- **LLM post-training** depends heavily on data quality, reward / verifier quality, rollout throughput, and stability of the optimization recipe.

---

## Websites and communities
- [Papers with Code - Reinforcement Learning](https://paperswithcode.com/task/reinforcement-learning)
- [Farama Foundation](https://farama.org/)
- [OpenDILab](https://opendilab.net/)
- [RLChina](http://rlchina.org/)
- [DeepRLHub](http://www.deeprlhub.com/)
- [Lilian Weng's blog](https://lilianweng.github.io/)

---

## Conferences and journals

### Conferences
- NeurIPS
- ICML
- ICLR
- AAAI
- IJCAI
- AAMAS
- CoRL
- RSS
- IROS

### Journals / venues often relevant to RL
- JMLR
- JAIR
- TMLR
- Autonomous Agents and Multi-Agent Systems
- IEEE TNNLS
- IEEE Transactions on Cybernetics

---

## Selected research groups

This section is intentionally **representative, not exhaustive**.

### Academia
- [UCL / David Silver](https://www.davidsilver.uk/)
- [BAIR / UC Berkeley](https://bair.berkeley.edu/)
- [Stanford CS234 / RL community](https://web.stanford.edu/class/cs234/)
- [CMU Deep RL](https://cmudeeprl.github.io/)
- [McGill / Mila](https://mila.quebec/en/)
- [NJU LAMDA](http://www.lamda.nju.edu.cn/)
- [PKU / Yaodong Yang](https://www.yangyaodong.com/)
- [SJTU APEX Lab](https://apex.sjtu.edu.cn/)
- [Tsinghua IIIS / Chongjie Zhang](http://people.iiis.tsinghua.edu.cn/~zhang/)
- [OpenDILab](https://opendilab.net/)

### Industry
- DeepMind
- OpenAI
- FAIR / Meta
- Microsoft Research
- Google Research
- Tencent
- Baidu
- Huawei Noah's Ark Lab
- Alibaba
- Polixir

---

## Contributing

Contributions are very welcome.

A good contribution usually has one of the following forms:
- add a missing classic resource;
- add a high-quality modern survey or benchmark;
- fix broken or outdated links;
- improve categorization;
- add a concise description explaining why a resource matters.

Please try to follow these principles:
- prefer official links;
- avoid duplicate entries;
- avoid unofficial PDF mirrors for copyrighted books;
- add a one-line description when the title alone is not self-explanatory.

If you find this repository helpful, consider giving it a star.

---

## Reference
- https://www.zhihu.com/collection/840642960
- https://www.zhihu.com/question/516672871
- http://www.deeprlhub.com/d/154/2
- https://zhuanlan.zhihu.com/p/571011569

---

If you have suggestions for expanding any subtopic such as **offline RL**, **model-based RL**, **MARL**, **RLHF**, **agent RL**, or **RL for recommender systems**, feel free to open an issue or PR.
