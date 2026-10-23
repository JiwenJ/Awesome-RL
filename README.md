
<h1 align="center">Awesome RL</h1>

<div align="center">

[![Awesome](https://raw.githubusercontent.com/sindresorhus/awesome/main/media/badge.svg)](https://github.com/sindresorhus/awesome)
![Static Badge](https://img.shields.io/badge/Status-Maintaining-%23ecfc03)
![Static Badge](https://img.shields.io/badge/PRs-Welcome-%23fc2003)

</div>

A curated list of reinforcement learning books, courses, research and industry groups, libraries, environments, communities, and events. Covers classical RL, offline and multi-agent RL, robot learning, world models, RLHF, and agent RL.


## Contents
- [Awesome RL](#awesome-rl)
   - [Books](#books)
   - [Courses](#courses)
   - [Research Group](#research-group)
   - [Industry Group](#industry-group)
   - [GitHub Repo](#github-repo)
   - [Website](#website)
   - [Activity](#activity)
   - [Community](#community)
   - [Conference & Journal](#publish)
   - [Misc](#misc)
   - [Contributing](#contributing)
   - [Reference](#reference)

---

## Books
- English
   - [Reinforcement Learning: An Introduction, 2nd edition](https://mitpress.mit.edu/9780262039246/reinforcement-learning/), by Richard S. Sutton and Andrew G. Barto. [[Author website]](http://incompleteideas.net/book/the-book-2nd.html) [[PDF (2020 revision)]](http://incompleteideas.net/book/RLbook2020.pdf) [Preferred]
   - [Algorithms for Reinforcement Learning](https://sites.ualberta.ca/~szepesva/rlbook.html), by Csaba Szepesvári. [[PDF]](https://www.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
   - [Reinforcement Learning for Sequential Decision and Optimal Control](https://link.springer.com/book/10.1007/978-981-19-7784-8), by Shengbo Eben Li.
   - [Dynamic Programming and Optimal Control, Volumes I and II](https://www.mit.edu/~dimitrib/dpbook.html), by Dimitri P. Bertsekas.
   - [Deep Reinforcement Learning Hands-On, 3rd edition](https://www.packtpub.com/en-gb/product/deep-reinforcement-learning-hands-on-9781835882702), by Maxim Lapan. [[Code]](https://github.com/PacktPublishing/Deep-Reinforcement-Learning-Hands-On-Third-Edition)
   - [Reinforcement Learning and Optimal Control](https://web.mit.edu/dimitrib/www/rlbook_athena.html), by Dimitri P. Bertsekas.
   - [Reinforcement Learning: Theory and Algorithms](https://rltheorybook.github.io/), by Alekh Agarwal, Kianté Brantley, Nan Jiang, Sham M. Kakade, and Wen Sun. (Working draft)
   - [Markov Decision Processes: Discrete Stochastic Dynamic Programming](https://onlinelibrary.wiley.com/doi/book/10.1002/9780470316887), by Martin L. Puterman.
   - [Neuro-Dynamic Programming](https://web.mit.edu/dimitrib/www/NDP.pdf), by Dimitri P. Bertsekas and John N. Tsitsiklis. (Author-hosted PDF)
   - [Multi-Agent Reinforcement Learning: Foundations and Modern Approaches](https://www.marl-book.com/), by Stefano V. Albrecht, Filippos Christianos, and Lukas Schäfer.
   - [Probabilistic Machine Learning: Advanced Topics](https://probml.github.io/pml-book/book2.html), by Kevin P. Murphy. (Background reading for model-based RL and sequential decision making)
   - [Bandit Algorithms](https://www.cambridge.org/core/books/bandit-algorithms/8E39FD004E6CE036680F90DD0C6F09FC), by Tor Lattimore and Csaba Szepesvári. [[PDF]](https://tor-lattimore.com/downloads/book/book.pdf)
   - [Distributional Reinforcement Learning](https://www.distributional-rl.org/), by Marc G. Bellemare, Will Dabney, and Mark Rowland.
   - [Algorithms for Decision Making](https://algorithmsbook.com/decisionmaking/), by Mykel J. Kochenderfer, Tim A. Wheeler, and Kyle H. Wray.
   - [Reinforcement Learning from Human Feedback](https://rlhfbook.com/), by Nathan Lambert. (Online book on RLHF and language-model post-training)
   - [Mastering Reinforcement Learning with Python](https://github.com/PacktPublishing/Mastering-Reinforcement-Learning-with-Python), by Enes Bilgin. (Publisher book description and companion code)
- Chinese
   - [动手学强化学习](https://hrl.boyuai.com/) 张伟楠 [[Code]](https://github.com/boyu-ai/Hands-on-RL)
   - 深度强化学习落地指南 魏宁 [[Publisher introduction]](https://developer.cloud.tencent.com/article/2280938)
   - 深度强化学习 王树森 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%BA%A6%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%20Deep%20Reinforcement%20Learning%20(%E7%8E%8B%E6%A0%91%E6%A3%AE%20%E9%BB%8E%E5%BD%A7%E5%90%9B%20%E5%BC%A0%E5%BF%97%E5%8D%8E).pdf)
   - [Easy RL：强化学习教程](https://datawhalechina.github.io/easy-rl/) 王琦 [[Repository]](https://github.com/datawhalechina/easy-rl)
   - 强化学习实战: 强化学习在阿里的技术演进和业务创新 笪庆 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%AE%9E%E6%88%98%EF%BC%9A%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%9C%A8%E9%98%BF%E9%87%8C%E7%9A%84%E6%8A%80%E6%9C%AF%E6%BC%94%E8%BF%9B%E5%92%8C%E4%B8%9A%E5%8A%A1%E5%88%9B%E6%96%B0%20(%E7%AC%AA%E5%BA%86%EF%BC%8C%E6%9B%BE%E5%AE%89%E7%A5%A5).pdf)
   - [深度强化学习](https://deepreinforcementlearningbook.org/) 董豪 (含中文 PDF 与配套代码)
   - 深入浅出强化学习：原理入门 郭宪 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%85%A5%E6%B5%85%E5%87%BA%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%9A%E5%8E%9F%E7%90%86%E5%85%A5%E9%97%A8-%E9%83%AD%E5%AE%AA-%E6%96%B9%E5%8B%87%E7%BA%AF.pdf)
   - [神经网络与深度学习](https://nndl.ai/nndl-v2/) 邱锡鹏 [[PDF (第二版出版前电子稿)]](https://github.com/nndl/nndl/releases/download/book-pdf/nndl-v2.pdf) (Background reading)
   - [机器学习](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/MLbook2016.htm) 周志华 (Background reading)
   - 统计强化学习: 现代机器学习方法 杉山将 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E7%BB%9F%E8%AE%A1%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%9A%E7%8E%B0%E4%BB%A3%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95-%E6%9D%89%E5%B1%B1%E5%B0%86.pdf)
   - 深度强化学习核心算法与应用 陈世勇 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%BA%A6%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E6%A0%B8%E5%BF%83%E7%AE%97%E6%B3%95%E4%B8%8E%E5%BA%94%E7%94%A8-(%E9%99%88%E4%B8%96%E5%8B%87-%E8%8B%8F%E5%8D%9A%E8%A7%88-%E6%9D%A8%E6%95%AC%E6%96%87).pdf)
   - 深度强化学习边做边学 小川雄太郎 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E6%B7%B1%E5%BA%A6%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E8%BE%B9%E5%81%9A%E8%BE%B9%E5%AD%A6%20(%E5%B0%8F%E5%B7%9D%E9%9B%84%E5%A4%AA%E9%83%8E(Yutaro%20Ogawa)%E8%91%97%20%E7%94%B3%E5%AF%8C%E9%A5%B6%E4%BA%8E%E5%83%A1%E8%AF%91).pdf)
   - 强化学习 邹伟 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%20(%E9%82%B9%E4%BC%9F%2C%20%E9%AC%B2%E7%8E%B2%2C%20%E5%88%98%E6%98%B1%E6%9D%93).pdf)
   - 强化学习精要: 核心算法与TensorFlow实现 冯超 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E7%B2%BE%E8%A6%81%20%E6%A0%B8%E5%BF%83%E7%AE%97%E6%B3%95%E4%B8%8ETensorFlow%E5%AE%9E%E7%8E%B0%20(%E5%86%AF%E8%B6%85).pdf)
   - 强化学习入门: 从原理到实践 叶强 [[PDF]](https://github.com/JiwenJ/Public-Books/blob/main/rl/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%85%A5%E9%97%A8%EF%BC%9A%E4%BB%8E%E5%8E%9F%E7%90%86%E5%88%B0%E5%AE%9E%E8%B7%B5%20(%E5%8F%B6%E5%BC%BA%20%20%E9%97%AB%E7%BB%B4%E6%96%B0%20%20%E9%BB%8E%E6%96%8C).pdf)

   *注：中文书目仅列第一作者；完整作者信息见所链接书页。*

---

## Courses

Years refer to the linked course offering; instructor names refer to that offering.

- UCL. [Reinforcement Learning (2015)](https://www.davidsilver.uk/teaching/). David Silver. [[Community notes and code]](https://github.com/dalmia/David-Silver-Reinforcement-learning)
- UCL / DeepMind. [Advanced Deep Learning and Reinforcement Learning (2018)](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs). [[Community archive of slides and assignments]](https://github.com/Zhenye-Na/advanced-deep-learning-and-reinforcement-learning-deepmind)
- MoFan Python. [Reinforcement Learning](https://mofanpy.com/tutorials/machine-learning/reinforcement-learning/) (Chinese).
- National Taiwan University. [Deep Reinforcement Learning, MLDS 2018](https://speech.ee.ntu.edu.tw/~hylee/mlds/2018-spring.php). Hung-yi Lee. [[Bilibili mirror]](https://www.bilibili.com/video/av24724071/)
- [Deep Reinforcement Learning](https://github.com/wangshusen/DRL). Shusen Wang. Slides, notes, and Chinese video lectures. [[Bilibili]](https://www.bilibili.com/video/BV12o4y197US/)
- [Intro to Reinforcement Learning / 强化学习纲要](https://github.com/zhoubolei/introRL). Bolei Zhou. Open online lectures, slides, and examples.
- UC Berkeley. [CS 185/285: Deep Reinforcement Learning](https://rail.eecs.berkeley.edu/deeprlcourse/). Sergey Levine. [[Previous offerings]](https://rail.eecs.berkeley.edu/deeprlcourse/resources/)
- Stanford. [CS234: Reinforcement Learning](https://web.stanford.edu/class/cs234/). Emma Brunskill. [[Bilibili mirror of the 2019 lectures]](https://www.bilibili.com/video/BV1sb411s7eQ/)
- Arizona State University. [CSE 691: Topics in Reinforcement Learning (Spring 2025)](https://www.mit.edu/~dimitrib/RLbook.html). Dimitri P. Bertsekas and Yuchao Li. Videos and slides; hosted on the instructor's MIT website. [[Syllabus]](https://www.mit.edu/~dimitrib/RLcourseoutline2025.pdf)
- Tsinghua University. Reinforcement Learning and Control / 强化学习与控制. Shengbo Eben Li. [[Course listing on the instructor's official profile]](https://www.svm.tsinghua.edu.cn/essay/80/2123.html)
- Carnegie Mellon University. [10-403: Deep Reinforcement Learning (Spring 2023)](https://cmudeeprl.github.io/403website_s23/). Katerina Fragkiadaki.
- Udacity. [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) (paid program). [[Public course code]](https://github.com/udacity/deep-reinforcement-learning)
- MIT. [6.S091: Introduction to Deep Reinforcement Learning (2019 lecture)](https://www.youtube.com/watch?v=zR11FLZ-O9M). Lex Fridman. [[Lecture collection]](https://deeplearning.mit.edu/)
- ETH Zurich. [Dynamic Programming and Optimal Control](https://idsc.ethz.ch/education/lectures/optimal-control.html). Raffaello D'Andrea.
- UC Berkeley. [Deep RL Bootcamp (2017)](https://sites.google.com/view/deep-rl-bootcamp/lectures). Pieter Abbeel and other instructors. Videos, slides, and practical foundations.
- Tsinghua University. [Advanced Machine Learning (2024)](https://dujh22.github.io/Dujinhua_wiki/aml2024/). Jie Tang. Course archive maintained by a teaching assistant; includes RL and RLHF modules.
- University of Illinois Urbana-Champaign. [CS 542: Statistical Reinforcement Learning](https://nanjiang.cs.illinois.edu/cs542/) and [CS 443: Reinforcement Learning](https://nanjiang.cs.illinois.edu/cs443/). Nan Jiang.
- University of Illinois Urbana-Champaign. [ECE 586: MDPs and Reinforcement Learning (Fall 2025)](https://courses.illinois.edu/schedule/2025/fall/ECE/586). R. Srikant. Course description.
- Duke University. [CompSci 590.7: Reinforcement Learning (Spring 2026)](https://courses.cs.duke.edu/compsci590.7/spring26/index.html). Ron Parr.
- Stanford. [EE 383 / MS&E 235B: Reinforcement Learning: Behaviors and Applications](https://bulletin.stanford.edu/courses/2253561). Benjamin Van Roy (2025–2026 offering). Course description.
- University of Michigan. [STATS 710: Sequential Decision Making with mHealth Applications (Fall 2016)](https://www.ambujtewari.com/teaching/STATS710-Fall2016/). Ambuj Tewari and Susan Murphy.
- Harvard. [STAT 234: Sequential Decision Making (Spring 2024)](https://people.seas.harvard.edu/~samurphy/teaching/stat234spring2024/syllabus.htm). Susan Murphy. Public syllabus and readings; some materials require Canvas access.
- Columbia University. [COMS E6998.001: Bandits and Reinforcement Learning (Fall 2017)](https://alekhagarwal.net/bandits_and_rl/). Alekh Agarwal and Alex Slivkins.
- Columbia University. [B9140-001: Dynamic Programming and Reinforcement Learning (Fall 2017)](https://djrusso.github.io/RLCourse/). Daniel Russo.
- Columbia University. [ORCS 4529 / IEOR 8100: Reinforcement Learning](https://www.columbia.edu/~sa3305/LectureNotes.htm). Shipra Agrawal. Lecture notes and slides.
- Carnegie Mellon University. [15-889e: Real Life Reinforcement Learning (Fall 2015)](https://www.cs.cmu.edu/~ebrun/15889e/index.html). Emma Brunskill.
- University of Massachusetts Amherst. [CMPSCI 687: Reinforcement Learning (Fall 2017 archive)](https://people.cs.umass.edu/~pthomas/courses/CMPSCI_687_Fall2017.html). Philip S. Thomas.
- Brown University. [CSCI2951-F: Learning and Sequential Decision Making (Fall 2017)](https://cs.brown.edu/courses/cs2951f/2017/). Michael L. Littman.
- Nanjing University. [Introduction to Reinforcement Learning](http://www.lamda.nju.edu.cn/introRL/). Yang Yu.
- Carnegie Mellon University. [16-745: Optimal Control and Reinforcement Learning](https://optimalcontrol.ri.cmu.edu/). Zachary Manchester.
- UCLA. [Reinforcement Learning of Large Language Models (Spring 2025)](https://ernestryu.com/courses/RL-LLM.html). Ernest K. Ryu. Covers PPO, GRPO, RLHF, and RLVR.
- OpenAI. [Spinning Up in Deep RL](https://spinningup.openai.com/en/latest/). Introductory explanations, exercises, and reference implementations.
- Hugging Face. [Deep Reinforcement Learning Course](https://huggingface.co/learn/deep-rl-course/en/unit0/introduction). Free theory and practical exercises; in low-maintenance mode, with the leaderboard and AI-vs-AI service unavailable.
- Stanford. [CS224R: Deep Reinforcement Learning](https://cs224r.stanford.edu/). Chelsea Finn. Includes imitation learning, offline RL, robotics, and language-model applications.
- Hugging Face. [LLM Course, Chapter 12: Build Reasoning Models](https://huggingface.co/learn/llm-course/en/chapter12/1). RL for LLMs and GRPO exercises using TRL.

---

## Research Group
* Asia
   * [CASIA](http://www.ia.cas.cn/)
     * Haifeng Zhang [[Homepage]](https://pkuzhf.github.io/) [[Group]](http://marl.ia.ac.cn/)
     * Zhiqiang Pu [[Homepage]](https://people.ucas.edu.cn/~pzq)
     * Dongbin Zhao [[Homepage]](https://people.ucas.ac.cn/~zhaodongbin)
   * [NJU](https://www.nju.edu.cn/en/)
     * LAMDA Group [[Group]](https://www.lamda.nju.edu.cn/)
     * Yang Yu [[Homepage]](https://www.lamda.nju.edu.cn/yuy/)
     * Yinghuan Shi [[Homepage]](https://cs.nju.edu.cn/shiyh/index.htm)
     * Yang Gao [[Homepage]](https://cs.nju.edu.cn/gaoyang/index.htm)
     * Zongzhang Zhang [[Homepage]](https://ai.nju.edu.cn/zhangzongzhang/index.htm)
   * [SJTU](https://en.sjtu.edu.cn/)
     * APEX Data and Knowledge Management Lab [[Group]](https://apex.sjtu.edu.cn/)
     * Yong Yu [[Homepage]](https://apex.sjtu.edu.cn/members/yyu)
     * Weinan Zhang [[Homepage]](https://wnzhang.net/)
     * Kai Yu [[Homepage]](https://x-lance.sjtu.edu.cn/~kaiyu/)
     * Ying Wen [[Homepage]](https://yingwen.io/)
   * [PKU](https://english.pku.edu.cn/)
     * PKU Alignment Group [[Group]](https://pku-alignment.group/)
     * Yaodong Yang [[Homepage]](https://yangyaodong.com/)
     * Zongqing Lu [[Homepage]](https://z0ngqing.github.io/)
     * Hao Dong [[Homepage]](https://zsdonghao.github.io/)
     * Zhihua Zhang [[Homepage]](https://math.pku.edu.cn/teachers/zhzhang/)
   * [THU](https://www.tsinghua.edu.cn/en/)
     * Junliang Xing [[Homepage]](https://www.cs.tsinghua.edu.cn/csen/info/1306/4423.htm)
     * Yi Wu (historical THU affiliation) [[Homepage]](https://jxwuyi.weebly.com/)
     * Shengbo Eben Li [[Homepage]](https://eng.svm.tsinghua.edu.cn/info/1025/1073.htm)
   * [USTC](https://en.ustc.edu.cn/)
     * Feng Wu [[Homepage]](https://wufeng02.github.io/)
     * Houqiang Li [[Homepage]](http://staff.ustc.edu.cn/~lihq/)
   * [CUHK-Shenzhen](https://www.cuhk.edu.cn/en)
     * Baoxiang Wang [[Homepage]](https://bxiangwang.github.io/)
     * Hongyuan Zha [[Homepage]](https://sds.cuhk.edu.cn/en/teacher/65)
   * [TJU](https://www.tju.edu.cn/)
     * Jianye Hao [[Homepage]](https://faculty-cn.tju.edu.cn/HAOJIANYE/en/index.htm)
   * [SIAT](https://english.siat.ac.cn/)
     * Yunduan Cui [[Homepage]](https://cuiyunduan.vercel.app/)
   * [HIT-SZ](https://en.hitsz.edu.cn/)
     * Yanjie Li [[Homepage]](https://homepage.hit.edu.cn/liyanjie)
   * [NTU Singapore](https://www.ntu.edu.sg/)
     * Bo An [[Homepage]](https://personal.ntu.edu.sg/boan/index.html)
     * Autonomous Agents Research Group [[Group]](https://agents-lab.org/)
     * Stefano V. Albrecht [[Homepage]](https://agents-lab.org/stefano-albrecht/)
   * [SYSU](https://www.sysu.edu.cn/sysuen/)
     * Chao Yu [[Homepage]](https://cse.sysu.edu.cn/teacher/Yuchao)
   * [KAIST](https://www.kaist.ac.kr/en/)
     * Smart Information Systems Research Lab (SISReL) [[Group]](https://sites.google.com/view/sisrelkaist)
     * Youngchul Sung [[Homepage]](https://ee.kaist.ac.kr/en/professor/12209/)
   * [OIST](https://www.oist.jp/)
     * Neural Computation Unit [[Group]](https://www.oist.jp/research/research-units/ncu)
     * Kenji Doya [[Homepage]](https://www.oist.jp/research/research-units/ncu/kenji-doya)
* North America
   * [McGill University](https://www.mcgill.ca/)
     * Reasoning and Learning Lab [[Group]](https://rl.cs.mcgill.ca/)
     * Doina Precup [[Homepage]](https://www.mcgill.ca/cim/precup)
     * Joelle Pineau [[Homepage]](https://www.mcgill.ca/cim/pineau)
   * [University of Alberta / Amii](https://www.amii.ca/)
     * RLAI Lab [[Group]](https://rlai.ualberta.ca/)
     * Michael Bowling [[Homepage]](https://bowlingmh.github.io/)
     * Richard Sutton [[Homepage]](https://www.amii.ca/people/richard-s-sutton)
     * Martha White [[Homepage]](https://apps.ualberta.ca/directory/person/whitem)
     * Adam White [[Homepage]](https://adamwhite.ca/)
     * Csaba Szepesvári [[Homepage]](https://sites.ualberta.ca/~szepesva/)
   * [UCLA](https://www.ucla.edu/)
     * Bolei Zhou [[Homepage]](https://boleizhou.github.io/)
   * [MIT](https://www.mit.edu/)
     * Improbable AI Lab [[Group]](https://people.csail.mit.edu/pulkitag/)
     * Robot Locomotion Group [[Group]](https://locomotion.csail.mit.edu/)
     * Pulkit Agrawal [[Homepage]](https://www.eecs.mit.edu/people/pulkit-agrawal/)
     * Leslie Kaelbling [[Homepage]](https://people.csail.mit.edu/lpk/)
     * Russ Tedrake [[Homepage]](https://www.csail.mit.edu/person/russ-tedrake)
     * Nicholas Roy [[Homepage]](https://www.csail.mit.edu/person/nicholas-roy)
     * Dimitri Bertsekas (in memoriam) [[Homepage]](https://www.mit.edu/~dimitrib/home.html)
   * [CMU](https://www.cmu.edu/)
     * Geoffrey Gordon [[Homepage]](https://www.cs.cmu.edu/~ggordon/)
     * Jeff Schneider [[Homepage]](https://www.cs.cmu.edu/~schneide/)
     * Andrew Moore (former faculty) [[Homepage]](https://www.cs.cmu.edu/~awm/)
     * Jessica K. Hodgins [[Homepage]](https://www.cs.cmu.edu/~jkh/)
     * Deepak Pathak [[Homepage]](https://www.cs.cmu.edu/~dpathak/)
     * Katerina Fragkiadaki [[Homepage]](https://www.cs.cmu.edu/~katef/)
   * [UC Berkeley](https://www.berkeley.edu/)
     * Berkeley AI Research [[Group]](https://bair.berkeley.edu/)
     * RAIL Lab [[Group]](https://rail.eecs.berkeley.edu/)
     * AUTOLAB [[Group]](https://autolab.berkeley.edu/)
     * Sergey Levine [[Homepage]](https://www2.eecs.berkeley.edu/Faculty/Homepages/svlevine.html)
     * Pieter Abbeel [[Homepage]](https://www2.eecs.berkeley.edu/Faculty/Homepages/abbeel.html)
     * Anca Dragan [[Homepage]](https://people.eecs.berkeley.edu/~anca/)
     * Ken Goldberg [[Homepage]](https://goldberg.berkeley.edu/)
     * Stuart Russell [[Homepage]](https://people.eecs.berkeley.edu/~russell/)
   * [Stanford University](https://www.stanford.edu/)
     * Stanford AI Lab [[Group]](https://ai.stanford.edu/)
     * IRIS Lab [[Group]](https://irislab.stanford.edu/)
     * ILIAD Lab [[Group]](https://iliad.stanford.edu/)
     * Benjamin Van Roy [[Homepage]](https://web.stanford.edu/~bvr/)
     * Emma Brunskill [[Homepage]](https://profiles.stanford.edu/emma-brunskill)
     * Mykel Kochenderfer [[Homepage]](https://profiles.stanford.edu/mykel-kochenderfer)
     * Dorsa Sadigh [[Homepage]](https://www.cs.stanford.edu/people/dorsa-sadigh)
     * Tengyu Ma [[Homepage]](https://profiles.stanford.edu/tengyu-ma)
     * Chelsea Finn [[Homepage]](https://profiles.stanford.edu/chelsea-finn)
     * Andrew Ng [[Homepage]](https://www.andrewng.org/)
   * [UIUC](https://illinois.edu/)
     * Nan Jiang [[Homepage]](https://nanjiang.cs.illinois.edu/)
   * [Duke University](https://www.duke.edu/)
     * Ronald Parr [[Homepage]](https://users.cs.duke.edu/~parr/)
   * [Brown University](https://www.brown.edu/)
     * Michael Littman [[Homepage]](https://www.littmania.com/)
   * [Columbia University](https://www.columbia.edu/)
     * Daniel Russo [[Homepage]](https://business.columbia.edu/faculty/people/daniel-russo)
     * Shipra Agrawal [[Homepage]](https://www.columbia.edu/~sa3305/)
   * [University of Toronto](https://www.utoronto.ca/)
     * Jimmy Ba [[Homepage]](https://jimmylba.github.io/)
     * Sheila McIlraith [[Homepage]](https://www.cs.toronto.edu/~sheila/)
   * [UT Austin](https://www.utexas.edu/)
     * Learning Agents Research Group [[Group]](https://www.cs.utexas.edu/~pstone/research.shtml)
     * Peter Stone [[Homepage]](https://www.cs.utexas.edu/~pstone/)
   * [UMass Amherst](https://www.umass.edu/)
     * Autonomous Learning Laboratory [[Group]](https://all.cs.umass.edu/)
     * Philip S. Thomas [[Homepage]](https://people.cs.umass.edu/~pthomas/)
     * Scott Niekum [[Homepage]](https://people.cs.umass.edu/~sniekum/)
   * [Harvard University](https://www.harvard.edu/)
     * Sham Kakade [[Homepage]](https://shamulent.github.io/)
   * [Princeton University](https://www.princeton.edu/)
     * Mengdi Wang [[Homepage]](https://ece.princeton.edu/people/mengdi-wang)
   * [Washington University in St. Louis](https://washu.edu/)
     * Machine Intelligence Group [[Group]](https://mig-ai.github.io/)
     * Chongjie Zhang [[Homepage]](https://engineering.washu.edu/faculty/Chongjie-Zhang.html)
* Europe
   * [INRIA](https://www.inria.fr/en)
     * Flowers AI & CogSci Lab [[Group]](https://flowers.inria.fr/)
   * [ETH Zurich](https://ethz.ch/en.html)
     * Learning and Adaptive Systems Group [[Group]](https://las.inf.ethz.ch/)
     * Andreas Krause [[Homepage]](https://las.inf.ethz.ch/krausea)
   * [University of Oxford](https://www.ox.ac.uk/)
     * Foerster Lab for AI Research (FLAIR) [[Group]](https://foersterlab.com/)
     * Whiteson Research Lab (WhiRL; historical Oxford lab) [[Group]](https://whirl.cs.ox.ac.uk/)
     * Jakob Foerster [[Homepage]](https://eng.ox.ac.uk/people/jakob-foerster/)
   * [University of Cambridge](https://www.cam.ac.uk/)
     * Machine Learning Group [[Group]](https://mlg.eng.cam.ac.uk/)
     * Carl Edward Rasmussen [[Homepage]](https://mlg.eng.cam.ac.uk/carl/)
   * [Imperial College London](https://www.imperial.ac.uk/)
     * Robot Learning Lab [[Group]](https://www.robot-learning.uk/)
     * Edward Johns [[Homepage]](https://profiles.imperial.ac.uk/e.johns)
   * [UCL](https://www.ucl.ac.uk/)
     * Centre for Artificial Intelligence [[Group]](https://www.ucl.ac.uk/engineering/research/centres-institutes-and-labs/ucl-centre-artificial-intelligence)
     * British Open-Ended Learning & Discovery (BOLD) Lab (joint with Oxford and Imperial) [[Group]](https://bold-lab.ai/)
     * Jun Wang [[Homepage]](https://profiles.ucl.ac.uk/10613-jun-wang)
     * David Silver [[Homepage]](https://www.davidsilver.uk/)
     * Marc Deisenroth [[Homepage]](https://www.deisenroth.cc/)
     * Tim Rocktäschel [[Homepage]](https://rockt.ai/)
   * [University of Amsterdam](https://www.uva.nl/en)
     * Amsterdam Machine Learning Lab (AMLab) [[Group]](https://amlab.science.uva.nl/)
     * Herke van Hoof [[Homepage]](https://amlab.science.uva.nl/people/HerkeVanHoof/)
   * [TU Delft](https://www.tudelft.nl/en/)
     * Sequential Decision Making Group [[Group]](https://research.tudelft.nl/en/organisations/sequential-decision-making/)
     * Frans Oliehoek [[Homepage]](https://www.fransoliehoek.net/)
   * [TU Darmstadt](https://www.tu-darmstadt.de/)
     * Intelligent Autonomous Systems (IAS) [[Group]](https://www.ias.informatik.tu-darmstadt.de/Main/IAS)
     * Jan Peters [[Homepage]](https://www.ias.informatik.tu-darmstadt.de/Team/JanPeters)
   * [University of Edinburgh](https://www.ed.ac.uk/)
     * Mistry Research Group [[Group]](https://homepages.inf.ed.ac.uk/mmistry/)
   * [University of Freiburg](https://uni-freiburg.de/en/)
     * Robot Learning Lab [[Group]](https://rl.uni-freiburg.de/)

* Oceania
   * [UNSW Sydney](https://www.unsw.edu.au/)
     * Machine Learning Group [[Group]](https://www.unsw.edu.au/engineering/our-schools/computer-science-and-engineering/our-research/research-groups/machine-learning)
     * Claude Sammut [[Homepage]](https://www.unsw.edu.au/staff/claude-sammut)
   * [Federation University Australia](https://www.federation.edu.au/)
     * Australian Responsible Autonomous Agents Collective (ARAAC; joint with Deakin University) [[Group]](https://araac.au/)
     * Peter Vamplew [[Homepage]](https://www.federation.edu.au/research/find-an-expert/peter-vamplew/)

#### Other outer link
- [Awesome-CV-Team](https://github.com/extreme-assistant/Awesome-CV-Team)


**[⬆ back to top](#contents)**
  
---

## Industry Group
* China
   * [Baidu](https://home.baidu.com/)
      * [PARL](https://github.com/PaddlePaddle/PARL)
   * [Tencent](https://www.tencent.com/)
   * [NetEase](https://www.netease.com/)
   * [ByteDance](https://www.bytedance.com/en/)
   * [DiDi](https://didiglobal.com/)
   * [Microsoft Research Asia (MSRA)](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/)
   * [Huawei](https://www.huawei.com/en/)
   * [Ping An](https://group.pingan.com/)
   * [Polixir](http://polixir.ai/) [[GitHub]](https://github.com/polixir)
   * [Inspir.ai](http://inspir.ai/) [[GitHub]](https://github.com/inspirai)
   * [Horizon Robotics](https://www.horizon.auto/en)
   * [Momenta](https://www.momenta.ai/en/)
   * [Parametrix.ai](https://www.parametrix.ai/)
   * [Alibaba Group](https://www.alibabagroup.com/)
   * [Kuaishou (Kwai)](https://www.kuaishou.com/en)
* Overseas
   * [OpenAI](https://openai.com/)
   * [Google DeepMind](https://deepmind.google/)
      * Shimon Whiteson [[Oxford profile]](https://www.cs.ox.ac.uk/people/shimon.whiteson/)
   * [Google Research - Learning Theory](https://research.google/teams/learning-theory/)
      * Alekh Agarwal [[Homepage]](https://alekhagarwal.net/)
   * [Microsoft Research New York City](https://www.microsoft.com/en-us/research/lab/microsoft-research-new-york/)
      * Alex Slivkins [[Homepage]](https://www.microsoft.com/en-us/research/people/slivkins/)
   * [Databricks AI Research](https://www.databricks.com/blog/category/research/ai-research)
      * Wen Sun [[Homepage]](https://wensun.github.io/)
   * [Meta Fundamental AI Research (FAIR)](https://ai.meta.com/research/)
   * [Salesforce AI Research](https://www.salesforce.com/ai-research/)
 
**[⬆ back to top](#contents)**

---
## GitHub Repo

### Learning implementations

- [rlcode/reinforcement-learning](https://github.com/rlcode/reinforcement-learning) — Single-file examples from tabular methods to deep RL.
- [Deep Reinforcement Learning Algorithms with PyTorch](https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch) — PyTorch algorithm implementations and experiments.
- [Deep Reinforcement Learning with PyTorch](https://github.com/sweetice/Deep-reinforcement-learning-with-pytorch) — Educational PyTorch implementations; examples use older dependency versions.
- [dennybritz/reinforcement-learning](https://github.com/dennybritz/reinforcement-learning) — Exercises and reference implementations accompanying Sutton & Barto and David Silver; uses legacy Gym/TensorFlow APIs.

### RL libraries

- [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) — RL algorithm implementations in PyTorch.
- [Google Dopamine](https://github.com/google/dopamine) — Compact research framework for prototyping and benchmarking RL algorithms.
- [CleanRL](https://github.com/vwxyzjn/cleanrl) — Single-file deep RL implementations with experiment tracking and evaluation tools.
- [RLlib](https://github.com/ray-project/ray) — Scalable RL library in Ray, including multi-agent and offline learning.
- [Acme](https://github.com/google-deepmind/acme) — RL building blocks and reference agents for research.
- [Tianshou](https://github.com/thu-ml/tianshou) — Modular PyTorch RL library with low-level and high-level training interfaces.
- [DI-engine](https://github.com/opendilab/DI-engine) — Decision intelligence framework supporting online, offline, multi-agent, and imitation learning.
- [Sample Factory](https://github.com/alex-petrenko/sample-factory) — High-throughput synchronous and asynchronous policy-gradient training.
- [TorchRL](https://github.com/pytorch/rl) — PyTorch components for environments, data collection, replay buffers, and RL objectives.
- [RLax](https://github.com/google-deepmind/rlax) — JAX building blocks for implementing RL algorithms.

### Multi-agent RL

- [PyMARL](https://github.com/oxwhirl/pymarl) — Cooperative multi-agent RL implementations, including QMIX, COMA, and VDN.
- [MARLlib](https://github.com/Replicable-MARL/MARLlib) — Multi-agent RL library built on Ray and RLlib.

### Environments and datasets

- [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) — Standard API and environments for multi-agent RL.
- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) — Standard RL environment API and successor to OpenAI Gym.
- [Minari](https://github.com/Farama-Foundation/Minari) — Offline RL dataset collection, storage, and access; successor for D4RL datasets.
- [D4RL](https://github.com/Farama-Foundation/D4RL) — Legacy offline RL benchmark; new dataset development has moved to Minari, with environments maintained in Farama projects.
- [MuJoCo](https://github.com/google-deepmind/mujoco) — Physics engine for robotics and control research.
- [robosuite](https://github.com/ARISE-Initiative/robosuite) — MuJoCo-based robot-learning simulation and benchmark environments.
- [ManiSkill](https://github.com/mani-skill/ManiSkill) — SAPIEN-based robot simulation and training framework focused on manipulation.
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) — GPU-accelerated framework for robot learning and simulation.
- [MuJoCo Playground](https://github.com/google-deepmind/mujoco_playground) — GPU-accelerated robot-learning environments built with MuJoCo MJX.

### LLM post-training

- [TRL](https://github.com/huggingface/trl) — Foundation-model post-training, including supervised fine-tuning, preference optimization, and RL.
- [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) — Distributed RLHF training framework.
- [verl](https://github.com/verl-project/verl) — RL training library for large language models based on HybridFlow.

---

## Website

- Papers with Code (Hugging Face revival): [classic RL](https://paperswithcode.co/tasks/classic-reinforcement-learning) and [RL for language models and agents](https://paperswithcode.co/tasks/reinforcement-learning) — papers, implementations, and benchmarks.
- [Hugging Face Papers](https://huggingface.co/papers) — recent machine learning papers and linked implementations.
- [从零开始推导贝尔曼方程](https://www.bilibili.com/video/BV1fN41197ES/)
- [强化学习知识大讲堂 — 郭宪](https://zhuanlan.zhihu.com/sharerl)
- [智能单元](https://zhuanlan.zhihu.com/intelligentunit)
- [神经网络与强化学习](https://zhuanlan.zhihu.com/c_101836530)
- [强化学习基础 David Silver 笔记 — 陈雄辉](https://zhuanlan.zhihu.com/c_135909947)
- [刘建平 Pinard 博客](https://www.cnblogs.com/pinard)
- [Lilian Weng's Lil'Log](https://lilianweng.github.io/) — explanations of RL, exploration, world models, and RLHF.
- [BAIR Blog](https://bair.berkeley.edu/blog/) — research articles from Berkeley Artificial Intelligence Research.

---

## Activity

- [Tencent AI Arena / 腾讯开悟](https://tencentarena.com/aiarena/zh/match) — Multi-agent RL competition portal and past editions; the 2026 competition is marked concluded.
- [DeepRacer on AWS](https://docs.aws.amazon.com/solutions/deepracer-on-aws/) — Open-source deployment for RL racing and community events. The former AWS-managed DeepRacer service ended on December 15, 2025 ([official FAQ](https://aws.amazon.com/deepracer/faqs/)).
- MineRL competition archives: [Diamond 2021](https://www.aicrowd.com/challenges/neurips-2021-minerl-diamond-competition) and [BASALT 2022](https://www.aicrowd.com/challenges/neurips-2022-minerl-basalt-competition) — Historical Minecraft challenges on sample efficiency and learning from human feedback.
- [NetHack Challenge 2021](https://nethackchallenge.com/) — Historical NeurIPS competition; [results and retrospective](https://nethackchallenge.com/report.html).

---

## Community

- [RLChina 强化学习社区](https://rlchina.org/)
- [DeepRLHub 深度强化学习实验室](https://www.deeprlhub.com/)
- [智源社区 (BAAI)](https://hub.baai.ac.cn/)
- [OpenDILab](https://opendilab.net/) — Shanghai AI Laboratory's decision intelligence community. [[GitHub]](https://github.com/opendilab)
- [Farama Foundation](https://farama.org/) — community and open-source standards for RL environments.
- [AI Alignment Forum](https://www.alignmentforum.org/) — technical discussions of alignment, including reward learning and RLHF.

---

## <div id="publish">Conference & Journal</div>

- **RL-specific venues:** [Reinforcement Learning Conference (RLC)](https://rl-conference.cc/) · [Reinforcement Learning Journal (RLJ)](https://rlj.org/).
- **Machine learning and AI conferences:** [NeurIPS](https://neurips.cc/) · [ICML](https://icml.cc/) · [ICLR](https://iclr.cc/) · [AAAI](https://aaai.org/conference/aaai/) · [IJCAI](https://ijcai.org/) · [AAMAS / IFAAMAS](https://www.ifaamas.org/).
- **Robot learning and robotics conferences:** [CoRL](https://www.corl.org/) · [RSS](https://roboticsconference.org/) · [IROS](https://www.ieee-ras.org/conferences-workshops/financially-co-sponsored/iros/).
- **Journals:** [JMLR](https://jmlr.org/) · [JAIR](https://www.jair.org/index.php/jair) · [Autonomous Agents and Multi-Agent Systems](https://link.springer.com/journal/10458) · [TMLR](https://jmlr.org/tmlr/).

---

## Misc

Mathematical references and supplementary learning guides:

- [Useful Inequalities Cheat Sheet](https://www.lkozma.net/inequalities_cheat_sheet/) — László Kozma.
- [Concentration of Measure](https://www.stat.cmu.edu/~larry/=sml/Concentration.pdf) — chapter by John Lafferty, Han Liu, and Larry Wasserman.
- [The Matrix Cookbook](https://www2.imm.dtu.dk/pubdb/edoc/imm3274.pdf) — Kaare Brandt Petersen and Michael Syskind Pedersen.
- [强化学习路线推荐及资料整理](https://zhuanlan.zhihu.com/p/344196096) — community learning guide.

**[⬆ back to top](#contents)**

---

## Contributing

Contributions are welcome through [pull requests](https://github.com/JiwenJ/Awesome-RL/pulls) or [issues](https://github.com/JiwenJ/Awesome-RL/issues).

- Preserve the existing section order and add resources to the most relevant section.
- Check for duplicates and prefer official author, publisher, course, or project links.
- Include a short description, and specify the edition or year when relevant.
- Fix outdated links and distinguish historical resources from currently maintained projects.

For questions about this list, contact [1546631808@qq.com](mailto:1546631808@qq.com).

**[⬆ back to top](#contents)**

---

## Reference

Earlier community lists consulted for this collection; affiliations and resource status may have changed since publication.

- [Zhihu collection](https://www.zhihu.com/collection/840642960)
- [Zhihu discussion](https://www.zhihu.com/question/516672871)
- [国内外做强化学习的老师，高校以及公司总结 — DeepRLHub](https://www.deeprlhub.com/d/154)
- [Zhihu article](https://zhuanlan.zhihu.com/p/571011569)
- [东栏雪 — Zhihu answer](https://www.zhihu.com/question/277325426/answer/2712724382)

**[⬆ back to top](#contents)**
