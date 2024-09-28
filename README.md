## Paper Collection of Multi-Agent Reinforcement Learning (MARL)

Multi-Agent Reinforcement Learning is a very interesting research area, which has strong connections with single-agent RL, multi-agent systems, game theory, evolutionary computation and optimization theory, and its application in Large Language Models (LLMs) and Robotics.

This is a collection of research and review papers of multi-agent reinforcement learning (MARL). The Papers are sorted by time. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact us.

## Overview
* [Tutorial](https://github.com/LantaoYu/MARL-Papers#tutorial-and-books)
* [Review Papers](https://github.com/LantaoYu/MARL-Papers#review-papers)
* [Research Papers](https://github.com/LantaoYu/MARL-Papers#research-papers)
  * [Framework](https://github.com/LantaoYu/MARL-Papers#framework)
  * [Joint action learning](https://github.com/LantaoYu/MARL-Papers#joint-action-learning)
  * [Cooperation and competition](https://github.com/LantaoYu/MARL-Papers#cooperation-and-competition)
  * [Coordination](https://github.com/LantaoYu/MARL-Papers#coordination)
  * [Security](https://github.com/LantaoYu/MARL-Papers#security)
  * [Self-Play](https://github.com/LantaoYu/MARL-Papers#self-play)
  * [Learning To Communicate](https://github.com/LantaoYu/MARL-Papers#learning-to-communicate)
  * [Transfer Learning](https://github.com/LantaoYu/MARL-Papers#transfer-learning)
  * [Imitation and Inverse Reinforcement Learning](https://github.com/LantaoYu/MARL-Papers#imitation-and-inverse-reinforcement-learning)
  * [Meta Learning](https://github.com/LantaoYu/MARL-Papers#meta-learning)
  * [Application](https://github.com/LantaoYu/MARL-Papers#application)
  * [Networked MARL (Decentralized Training Decentralized Execution)](https://github.com/LantaoYu/MARL-Papers#networked-MARL)
  * [MARL in LLMs (MARL in Large Language Models)](https://github.com/LantaoYu/MARL-Papers#framework)
  * [MARL in Robotics (MARL in Robotics)](https://github.com/LantaoYu/MARL-Papers#framework)
  

## Tutorial and Books
* [Multi-Agent Reinforcement Learning: Foundations and Modern Approaches](https://www.marl-book.com/download) by Stefano V. Albrecht, Filippos Christianos, Lukas Schäfer, 2023.
* [Many-agent Reinforcement Learning](https://discovery.ucl.ac.uk/id/eprint/10124273/12/Yang_10124273_thesis_revised.pdf) by Yaodong Yang, 2021. PhD Thesis.
* [Deep Multi-Agent Reinforcement Learning](https://ora.ox.ac.uk/objects/uuid:a55621b3-53c0-4e1b-ad1c-92438b57ffa4) by Jakob N Foerster, 2018. PhD Thesis.
* [Multi-Agent Machine Learning: A Reinforcement Approach](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118884614) by H. M. Schwartz, 2014.
* [Multiagent Reinforcement Learning](http://www.ecmlpkdd2013.org/wp-content/uploads/2013/09/Multiagent-Reinforcement-Learning.pdf) by Daan Bloembergen, Daniel Hennes, Michael Kaisers, Peter Vrancx. ECML, 2013.
* [Multiagent systems: Algorithmic, game-theoretic, and logical foundations](http://www.masfoundations.org/download.html) by Shoham Y, Leyton-Brown K. Cambridge University Press, 2008.

## Review Papers
* [Model-based Multi-agent Reinforcement Learning: Recent Progress and Prospects](https://arxiv.org/pdf/2203.10603.pdf) by Xihuai Wang, Zhicheng Zhang, and Weinan Zhang. 2022.
* [An overview of multi-agent reinforcement learning from game theoretical perspective](https://arxiv.org/pdf/2011.00583.pdf) by Yaodong Yang and Jun Wang. 2020.
* [A Survey and Critique of Multiagent Deep Reinforcement Learning](https://arxiv.org/abs/1810.05587) by Pablo Hernandez-Leal, Bilal Kartal and Matthew E. Taylor. 2019.
* [Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms](https://arxiv.org/pdf/1911.10635.pdf) by Kaiqing Zhang, Zhuoran Yang, Tamer Başar. 2019.
* [A Survey on Transfer Learning for Multiagent Reinforcement Learning Systems](https://www.jair.org/index.php/jair/article/view/11396) by Silva, Felipe Leno da; Costa, Anna Helena Reali. JAIR, 2019.
* [Autonomously Reusing Knowledge in Multiagent Reinforcement Learning](https://www.ijcai.org/proceedings/2018/774) by Silva, Felipe Leno da; Taylor, Matthew E.; Costa, Anna Helena Reali. IJCAI, 2018.
* [Deep Reinforcement Learning Variants of Multi-Agent Learning Algorithms](https://project-archive.inf.ed.ac.uk/msc/20162091/msc_proj.pdf) by Castaneda A O. 2016.
* [Evolutionary Dynamics of Multi-Agent Learning: A Survey](https://www.jair.org/index.php/jair/article/view/10952) by Bloembergen, Daan, et al. JAIR, 2015.
* [Game theory and multi-agent reinforcement learning](https://www.researchgate.net/publication/269100101_Game_Theory_and_Multi-agent_Reinforcement_Learning) by Nowé A, Vrancx P, De Hauwere Y M. Reinforcement Learning. Springer Berlin Heidelberg, 2012.
* [Multi-agent reinforcement learning: An overview](http://www.dcsc.tudelft.nl/~bdeschutter/pub/rep/10_003.pdf) by Buşoniu L, Babuška R, De Schutter B. Innovations in multi-agent systems and applications-1. Springer Berlin Heidelberg, 2010
* [A comprehensive survey of multi-agent reinforcement learning](http://www.dcsc.tudelft.nl/~bdeschutter/pub/rep/07_019.pdf) by Busoniu L, Babuska R, De Schutter B. IEEE Transactions on Systems Man and Cybernetics Part C Applications and Reviews, 2008
* [If multi-agent learning is the answer, what is the question?](http://robotics.stanford.edu/~shoham/www%20papers/LearningInMAS.pdf) by Shoham Y, Powers R, Grenager T. Artificial Intelligence, 2007.
* [From single-agent to multi-agent reinforcement learning: Foundational concepts and methods](http://users.isr.ist.utl.pt/~mtjspaan/readingGroup/learningNeto05.pdf) by Neto G. Learning theory course, 2005.
* [Evolutionary game theory and multi-agent reinforcement learning](https://pdfs.semanticscholar.org/bb9f/bee22eae2b47bbf304804a6ac07def1aecdb.pdf) by Tuyls K, Nowé A. The Knowledge Engineering Review, 2005.
* [An Overview of Cooperative and Competitive Multiagent Learning](https://www.researchgate.net/publication/221622801_An_Overview_of_Cooperative_and_Competitive_Multiagent_Learning) by Pieter Jan ’t HoenKarl TuylsLiviu PanaitSean LukeJ. A. La Poutré. AAMAS's workshop LAMAS, 2005.
* [Cooperative multi-agent learning: the state of the art](https://cs.gmu.edu/~eclab/papers/panait05cooperative.pdf) by Liviu Panait and Sean Luke, 2005.

## Research Papers

### MARL in LLMs
* [Mutual Theory of Mind in Human-AI Collaboration: An Empirical Study with LLM-driven AI Agents in a Real-time Shared Workspace Task](https://arxiv.org/abs/2409.08811.pdf) by Shao Zhang*, Xihuai Wang*, Wenhao Zhang, Yongshan Chen, Landi Gao, Dakuo Wang, Weinan Zhang, Xinbing Wang, and Ying Wen. 2024.
* [Large language model based multi-agents: A survey of progress and challenges](https://arxiv.org/pdf/2402.01680) by Guo, Taicheng, Xiuying Chen, Yaqi Wang, Ruidi Chang, Shichao Pei, Nitesh V. Chawla, Olaf Wiest, and Xiangliang Zhang. 2024.
* [Leveraging Large Language Models for Optimised Coordination in Textual Multi-Agent Reinforcement Learning](https://openreview.net/pdf?id=1PPjf4wife) by Slumbers, Oliver, David Henry Mguni, Kun Shao, and Jun Wang. 2024.
* [Theory of mind for multi-agent collaboration via large language models](https://arxiv.org/pdf/2310.10701) by Li, Huao, Yu Quan Chong, Simon Stepputtis, Joseph Campbell, Dana Hughes, Michael Lewis, and Katia Sycara. 2023.


### Framework
* [Multi-Agent Constrained Policy Optimisation](https://arxiv.org/pdf/2110.02793.pdf) by Shangding Gu, Jakub Grudzien Kuba, Munning Wen, Ruiqing Chen, Ziyan Wang, Zheng Tian, Jun Wang, Alois Knoll, and Yaodong Yang, 2021.
* [Settling the Variance of Multi-Agent Policy Gradients](https://arxiv.org/pdf/2108.08612.pdf) by Kuba Jakub, Muning Wen, Linghui Meng, Shangding Gu, Haifeng Zhang, David Mguni, Jun Wang, and Yaodong Yang, NIPS 2021.
* [QMIX: Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1803.11485.pdf) by Tabish Rashid, Mikayel Samvelyan, Christian Schroeder de Witt, Gregory Farquhar, Jakob Foerster, Shimon Whiteson. ICML 2018.
* [Mean Field Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1802.05438.pdf) by Yaodong Yang, Rui Luo, Minne Li, Ming Zhou, Weinan Zhang, and Jun Wang. ICML 2018.
* [Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments](https://arxiv.org/pdf/1706.02275.pdf) by Lowe R, Wu Y, Tamar A, et al. arXiv, 2017.
* [Deep Decentralized Multi-task Multi-Agent RL under Partial Observability](https://arxiv.org/pdf/1703.06182.pdf) by Omidshafiei S, Pazis J, Amato C, et al. arXiv, 2017.
* [Multiagent Bidirectionally-Coordinated Nets for Learning to Play StarCraft Combat Games](https://arxiv.org/pdf/1703.10069.pdf) by Peng P, Yuan Q, Wen Y, et al. arXiv, 2017.
* [Robust Adversarial Reinforcement Learning](https://arxiv.org/pdf/1703.02702.pdf) by Lerrel Pinto, James Davidson, Rahul Sukthankar, Abhinav Gupta. arXiv, 2017.
* [Stabilising Experience Replay for Deep Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1702.08887.pdf) by Foerster J, Nardelli N, Farquhar G, et al. arXiv, 2017.
* [Multiagent reinforcement learning with sparse interactions by negotiation and knowledge transfer](https://arxiv.org/pdf/1508.05328.pdf) by Zhou L, Yang P, Chen C, et al. IEEE transactions on cybernetics, 2016.
* [Decentralised multi-agent reinforcement learning for dynamic and uncertain environments](https://arxiv.org/pdf/1409.4561.pdf) by Marinescu A, Dusparic I, Taylor A, et al. arXiv, 2014.
* [CLEANing the reward: counterfactual actions to remove exploratory action noise in multiagent learning](http://irll.eecs.wsu.edu/wp-content/papercite-data/pdf/2014iat-holmesparker.pdf) by HolmesParker C, Taylor M E, Agogino A, et al. AAMAS, 2014.
* [Bayesian reinforcement learning for multiagent systems with state uncertainty](http://www.fransoliehoek.net/docs/Amato13MSDM.pdf) by Amato C, Oliehoek F A. MSDM Workshop, 2013.
* [Multiagent learning: Basics, challenges, and prospects](http://www.weiss-gerhard.info/publications/AI_MAGAZINE_2012_TuylsWeiss.pdf) by Tuyls, Karl, and Gerhard Weiss. AI Magazine, 2012.
* [Classes of multiagent q-learning dynamics with epsilon-greedy exploration](http://icml2010.haifa.il.ibm.com/papers/191.pdf) by Wunder M, Littman M L, Babes M. ICML, 2010.
* [Conditional random fields for multi-agent reinforcement learning](http://www.machinelearning.org/proceedings/icml2007/papers/89.pdf) by Zhang X, Aberdeen D, Vishwanathan S V N. ICML, 2007.
* [Multi-agent reinforcement learning using strategies and voting](http://ama.imag.fr/~partalas/partalasmarl.pdf) by Partalas, Ioannis, Ioannis Feneris, and Ioannis Vlahavas. ICTAI, 2007.
* [A reinforcement learning scheme for a partially-observable multi-agent game](https://pdfs.semanticscholar.org/57fb/ae00e17c0d798559ebab0e8f4267e032f41d.pdf) by Ishii S, Fujita H, Mitsutake M, et al. Machine Learning, 2005.
* [Asymmetric multiagent reinforcement learning](http://lib.tkk.fi/Diss/2004/isbn9512273594/article1.pdf) by Könönen V. Web Intelligence and Agent Systems, 2004.
* [Adaptive policy gradient in multiagent learning](http://dl.acm.org/citation.cfm?id=860686) by Banerjee B, Peng J. AAMAS, 2003.
* [Reinforcement learning to play an optimal Nash equilibrium in team Markov games](https://papers.nips.cc/paper/2171-reinforcement-learning-to-play-an-optimal-nash-equilibrium-in-team-markov-games.pdf) by Wang X, Sandholm T. NIPS, 2002.
* [Multiagent learning using a variable learning rate](https://www.sciencedirect.com/science/article/pii/S0004370202001212) by Michael Bowling and Manuela Veloso, 2002.
* [Value-function reinforcement learning in Markov game](http://www.sts.rpi.edu/~rsun/si-mal/article3.pdf) by Littman M L. Cognitive Systems Research, 2001.
* [Hierarchical multi-agent reinforcement learning](http://researchers.lille.inria.fr/~ghavamza/my_website/Publications_files/agents01.pdf) by Makar, Rajbala, Sridhar Mahadevan, and Mohammad Ghavamzadeh. The fifth international conference on Autonomous agents, 2001.
* [An analysis of stochastic game theory for multiagent reinforcement learning](https://www.cs.cmu.edu/~mmv/papers/00TR-mike.pdf) by Michael Bowling and Manuela Veloso, 2000.

### Joint action learning
* [AWESOME: A general multiagent learning algorithm that converges in self-play and learns a best response against stationary opponents](http://www.cs.cmu.edu/~conitzer/awesomeML06.pdf) by Conitzer V, Sandholm T. Machine Learning, 2007.
* [Extending Q-Learning to General Adaptive Multi-Agent Systems](https://papers.nips.cc/paper/2503-extending-q-learning-to-general-adaptive-multi-agent-systems.pdf) by Tesauro, Gerald. NIPS, 2003.
* [Multiagent reinforcement learning: theoretical framework and an algorithm.](http://www.lirmm.fr/~jq/Cours/3cycle/module/HuWellman98icml.pdf) by Hu, Junling, and Michael P. Wellman. ICML, 1998.
* [The dynamics of reinforcement learning in cooperative multiagent systems](http://www.aaai.org/Papers/AAAI/1998/AAAI98-106.pdf) by Claus C, Boutilier C. AAAI, 1998.
* [Markov games as a framework for multi-agent reinforcement learning](https://www.cs.duke.edu/courses/spring07/cps296.3/littman94markov.pdf) by Littman, Michael L. ICML, 1994.

### Cooperation and competition
* [Order Matters: Agent-by-agent Policy Optimization](https://arxiv.org/pdf/2302.06205.pdf) by Xihuai Wang, Zheng Tian, Ziyu Wan, Ying Wen, Jun Wang, Weinan Zhang, ICLR 2023.
* [Interaction Pattern Disentangling for Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2207.03902.pdf) by Shunyu Liu, Jie Song, Yihe Zhou, Na Yu, Kaixuan Chen, Zunlei Feng, Mingli Song. TPAMI, 2024.
* [Contrastive Identity-Aware Learning for Multi-Agent Value Decomposition](https://arxiv.org/pdf/2211.12712.pdf) by Shunyu Liu, Yihe Zhou, Jie Song, Tongya Zheng, Kaixuan Chen, Tongtian Zhu, Zunlei Feng, Mingli Song. AAAI, 2023.
* [Is Centralized Training with Decentralized Execution Framework Centralized Enough for MARL?](https://arxiv.org/pdf/2305.17352.pdf) by Yihe Zhou, Shunyu Liu, Yunpeng Qing, Kaixuan Chen, Tongya Zheng, Yanhao Huang, Jie Song, Mingli Song. 2023.
* [Multi-Agent Reinforcement Learning is a Sequence Modeling Problem](https://arxiv.org/pdf/2205.14953.pdf), by Wen, Muning, Jakub Grudzien Kuba, Runji Lin, Weinan Zhang, Ying Wen, Jun Wang, and Yaodong Yang, 2022.
* [The Complexity of Markov Equilibrium in Stochastic Games](https://arxiv.org/pdf/2204.03991.pdf) by Daskalakis, Constantinos, Noah Golowich, and Kaiqing Zhang, 2022.
* [Trust region policy optimisation in multi-agent reinforcement learning](https://arxiv.org/pdf/2109.11251.pdf) by Kuba, Jakub Grudzien, Ruiqing Chen, Munning Wen, Ying Wen, Fanglei Sun, Jun Wang, and Yaodong Yang, ICLR 2022.
* [Model-based Multi-agent Policy Optimization with Adaptive Opponent-wise Rollouts](https://arxiv.org/pdf/2203.10603.pdf) by Weinan Zhang, Xihuai Wang, Jian Shen, and Ming Zhou. IJCAI 2021.
* [The Surprising Effectiveness of PPO in Cooperative, Multi-Agent Games](https://arxiv.org/pdf/2103.01955.pdf) by Chao Yu, Akash Velu, Eugene Vinitsky, Yu Wang, Alexandre Bayen, Yi Wu, 2021.
* [Human-level performance in 3D multiplayer games with population-based reinforcement learning](https://www.science.org/doi/abs/10.1126/science.aau6249) by Max Jaderberg, Wojciech M. Czarnecki, Iain Dunning, et al. Science 364.6443: 859-865, 2019.
* [Emergent complexity through multi-agent competition](https://arxiv.org/pdf/1710.03748.pdf) by Trapit Bansal, Jakub Pachocki, Szymon Sidor, Ilya Sutskever, Igor Mordatch, 2018.
* [Learning with opponent learning awareness](https://arxiv.org/pdf/1709.04326.pdf) by Jakob Foerster, Richard Y. Chen2, Maruan Al-Shedivat, Shimon Whiteson, Pieter Abbeel, Igor Mordatch, 2018.
* [Multi-agent Reinforcement Learning in Sequential Social Dilemmas](https://arxiv.org/pdf/1702.03037.pdf) by Leibo J Z, Zambaldi V, Lanctot M, et al. arXiv, 2017. [[Post](https://deepmind.com/blog/understanding-agent-cooperation/)]
* [Cooperative Multi-Agent Control Using Deep Reinforcement Learning](https://ala2017.it.nuigalway.ie/papers/ALA2017_Gupta.pdf) by Gupta, J. K., Egorov, M., & Kochenderfer, M. AAMAS 2017.
* [Reinforcement Learning in Partially Observable Multiagent Settings: Monte Carlo Exploring Policies with PAC Bounds](http://orca.st.usm.edu/~banerjee/papers/p530-ceren.pdf) by Roi Ceren, Prashant Doshi, and Bikramjit Banerjee, pp. 530-538, AAMAS 2016.
* [Opponent Modeling in Deep Reinforcement Learning](http://www.umiacs.umd.edu/~hal/docs/daume16opponent.pdf) by He H, Boyd-Graber J, Kwok K, et al. ICML, 2016.
* [Multiagent cooperation and competition with deep reinforcement learning](https://arxiv.org/pdf/1511.08779.pdf) by Tampuu A, Matiisen T, Kodelja D, et al. arXiv, 2015.
* [Emotional multiagent reinforcement learning in social dilemmas](http://www.uow.edu.au/~fren/documents/EMR_2013.pdf) by Yu C, Zhang M, Ren F. International Conference on Principles and Practice of Multi-Agent Systems, 2013.
* [Multi-agent reinforcement learning in common interest and fixed sum stochastic games: An experimental study](http://www.jmlr.org/papers/volume9/bab08a/bab08a.pdf) by Bab, Avraham, and Ronen I. Brafman. Journal of Machine Learning Research, 2008.
* [Combining policy search with planning in multi-agent cooperation](https://pdfs.semanticscholar.org/5120/d9f2c738ad223e9f8f14cb3fd5612239a35c.pdf) by Ma J, Cameron S. Robot Soccer World Cup, 2008.
* [Collaborative multiagent reinforcement learning by payoff propagation](http://www.jmlr.org/papers/volume7/kok06a/kok06a.pdf) by Kok J R, Vlassis N. JMLR, 2006.
* [Learning to cooperate in multi-agent social dilemmas](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.107.335&rep=rep1&type=pdf) by de Cote E M, Lazaric A, Restelli M. AAMAS, 2006.
* [Learning to compete, compromise, and cooperate in repeated general-sum games](http://www.machinelearning.org/proceedings/icml2005/papers/021_Learning_CrandallGoodrich.pdf) by Crandall J W, Goodrich M A. ICML, 2005.
* [Sparse cooperative Q-learning](http://www.machinelearning.org/proceedings/icml2004/papers/267.pdf) by Kok J R, Vlassis N. ICML, 2004.
* [Global Convergence of Multi-Agent Policy Gradient in Markov Potential Games](https://arxiv.org/pdf/2106.01969.pdf) by Leonardos, Stefanos, Will Overman, Ioannis Panageas, and Georgios Piliouras. 2021
* [Markov α-Potential Games: Equilibrium Approximation and Regret Analysis](https://arxiv.org/pdf/2305.12553.pdf) by Xin G, et al, 2023
* [A Natural Actor-Critic Framework for Zero-Sum Markov Games](https://proceedings.mlr.press/v162/alacaoglu22a/alacaoglu22a.pdf) Ahmet A. et al, ICML, 2022

### Coordination
* [ZSC-Eval: An Evaluation Toolkit and Benchmark for Multi-agent Zero-shot Coordination](https://arxiv.org/pdf/2310.05208.pdf) by Xihuai Wang, Shao Zhang, Wenhao Zhang, Wentao Dong, Jingxiao Chen, Ying Wen, and Weinan Zhang. NeurIPS 2024.
* [Collaborating with Humans without Human Data](https://openreview.net/pdf?id=1Kof-nkmQB8) by DJ Strouse, Kevin R. McKee, Matt Botvinick, Edward Hughes, Richard Everett. NeurIPS 2021.
* [Coordinated Multi-Agent Imitation Learning](https://arxiv.org/pdf/1703.03121.pdf) by Le H M, Yue Y, Carr P. arXiv, 2017.
* [Reinforcement social learning of coordination in networked cooperative multiagent systems](http://mipc.inf.ed.ac.uk/2014/papers/mipc2014_hao_etal.pdf) by Hao J, Huang D, Cai Y, et al. AAAI Workshop, 2014.
* [Coordinating multi-agent reinforcement learning with limited communication](http://www.aamas-conference.org/Proceedings/aamas2013/docs/p1101.pdf) by Zhang, Chongjie, and Victor Lesser. AAMAS, 2013.
* [Coordination guided reinforcement learning](http://www.ifaamas.org/Proceedings/aamas2012/papers/1B_1.pdf) by Lau Q P, Lee M L, Hsu W. AAMAS, 2012.
* [Coordination in multiagent reinforcement learning: a Bayesian approach](https://www.cs.toronto.edu/~cebly/Papers/bayesMARL.pdf) by Chalkiadakis G, Boutilier C. AAMAS, 2003.
* [Coordinated reinforcement learning](https://users.cs.duke.edu/~parr/icml02.pdf) by Guestrin C, Lagoudakis M, Parr R. ICML, 2002.
* [Reinforcement learning of coordination in cooperative multi-agent systems](http://www.aaai.org/Papers/AAAI/2002/AAAI02-050.pdf) by Kapetanakis S, Kudenko D. AAAI/IAAI, 2002.

### Security
* [Markov Security Games: Learning in Spatial Security Problems](http://www.fransoliehoek.net/docs/Klima16LICMAS.pdf) by Klima R, Tuyls K, Oliehoek F. The Learning, Inference and Control of Multi-Agent Systems at NIPS, 2016.
* [Cooperative Capture by Multi-Agent using Reinforcement Learning, Application for Security Patrol Systems](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7244682) by Yasuyuki S, Hirofumi O, Tadashi M, et al. Control Conference (ASCC), 2015
* [Improving learning and adaptation in security games by exploiting information asymmetry](http://www4.ncsu.edu/~hdai/infocom-2015-XH.pdf) by He X, Dai H, Ning P. INFOCOM, 2015.

### Self-Play
* [A Comparison of Self-Play Algorithms Under a Generalized Framework](https://arxiv.org/abs/2006.04471) by Daniel Hernandez, Kevin Denamganai, Sam Devlin, et al. IEEE Transactions on Games 2021
* [A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning](https://arxiv.org/pdf/1711.00832.pdf) by Marc Lanctot, Vinicius Zambaldi, Audrunas Gruslys, Angeliki Lazaridou, Karl Tuyls, Julien Perolat, David Silver, Thore Graepel. NIPS 2017.
* [Deep reinforcement learning from self-play in imperfect-information games](https://arxiv.org/pdf/1603.01121.pdf) by Heinrich, Johannes, and David Silver. arXiv, 2016.
* [Fictitious Self-Play in Extensive-Form Games](http://jmlr.org/proceedings/papers/v37/heinrich15.pdf) by Heinrich, Johannes, Marc Lanctot, and David Silver. ICML, 2015.

### Learning To Communicate
* [Hammer: Multi-level coordination of reinforcement learning agents via learned messaging] by Nikunj Gupta, G. Srinivasaraghavan, Swarup Mohalik, Nishant Kumar, and Matthew E. Taylor, Neural Computing and Applications, 2023." 
* [Learning to ground multi-agent communication with autoencoders](https://arxiv.org/pdf/2110.15349) by Lin, Toru, Jacob Huh, Christopher Stauffer, Ser Nam Lim, and Phillip Isola. 2021.
* [Emergent Communication through Negotiation](https://openreview.net/pdf?id=Hk6WhagRW) by Kris Cao, Angeliki Lazaridou, Marc Lanctot, Joel Z Leibo, Karl Tuyls, Stephen Clark, 2018.
* [Emergence of Linguistic Communication From Referential Games with Symbolic and Pixel Input](https://openreview.net/pdf?id=HJGv1Z-AW) by Angeliki Lazaridou, Karl Moritz Hermann, Karl Tuyls, Stephen Clark. ICLR 2018.
* [Emergence of Language with Multi-agent Games: Learning to Communicate with Sequences of Symbols](https://openreview.net/pdf?id=SkaxnKEYg) by Serhii Havrylov, Ivan Titov. ICLR Workshop, 2017.
* [Learning Cooperative Visual Dialog Agents with Deep Reinforcement Learning](https://arxiv.org/pdf/1703.06585.pdf) by Abhishek Das, Satwik Kottur, et al. arXiv, 2017.
* [Emergence of Grounded Compositional Language in Multi-Agent Populations](https://arxiv.org/pdf/1703.04908.pdf) by Igor Mordatch, Pieter Abbeel. arXiv, 2017. [[Post](https://openai.com/blog/learning-to-communicate/)]
* [Cooperation and communication in multiagent deep reinforcement learning](https://repositories.lib.utexas.edu/handle/2152/45681) by Hausknecht M J. 2017.
* [Multi-agent cooperation and the emergence of (natural) language](https://openreview.net/pdf?id=Hk8N3Sclg) by Lazaridou A, Peysakhovich A, Baroni M. arXiv, 2016.
* [Learning to communicate to solve riddles with deep distributed recurrent q-networks](https://arxiv.org/pdf/1602.02672.pdf) by Foerster J N, Assael Y M, de Freitas N, et al. arXiv, 2016.
* [Learning to communicate with deep multi-agent reinforcement learning](https://arxiv.org/pdf/1605.06676.pdf) by Foerster J, Assael Y M, de Freitas N, et al. NIPS, 2016.
* [Learning multiagent communication with backpropagation](http://papers.nips.cc/paper/6398-learning-multiagent-communication-with-backpropagation.pdf) by Sukhbaatar S, Fergus R. NIPS, 2016.
* [Efficient distributed reinforcement learning through agreement](http://people.csail.mit.edu/lpk/papers/dars08.pdf) by Varshavskaya P, Kaelbling L P, Rus D. Distributed Autonomous Robotic Systems, 2009.

### Transfer Learning
* [Simultaneously Learning and Advising in Multiagent Reinforcement Learning](http://www.ifaamas.org/Proceedings/aamas2017/pdfs/p1100.pdf) by Silva, Felipe Leno da; Glatt, Ruben; and Costa, Anna Helena Reali. AAMAS, 2017.
* [Accelerating Multiagent Reinforcement Learning through Transfer Learning](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14217/14005) by Silva, Felipe Leno da; and Costa, Anna Helena Reali. AAAI, 2017.
* [Accelerating multi-agent reinforcement learning with dynamic co-learning](https://web.cs.umass.edu/publication/docs/2015/UM-CS-2015-004.pdf) by Garant D, da Silva B C, Lesser V, et al. Technical report, 2015
* [Transfer learning in multi-agent systems through parallel transfer](https://www.scss.tcd.ie/~tayloral/res/papers/Taylor_ParallelTransferLearning_ICML_2013.pdf) by Taylor, Adam, et al. ICML, 2013.
* [Transfer learning in multi-agent reinforcement learning domains](https://ewrl.files.wordpress.com/2011/08/ewrl2011_submission_19.pdf) by Boutsioukis, Georgios, Ioannis Partalas, and Ioannis Vlahavas. European Workshop on Reinforcement Learning, 2011.
* [Transfer Learning for Multi-agent Coordination](https://ai.vub.ac.be/~ydehauwe/publications/ICAART2011_2.pdf) by Vrancx, Peter, Yann-Michaël De Hauwere, and Ann Nowé. ICAART, 2011.

### Imitation and Inverse Reinforcement Learning
* [On the Utility of Learning about Humans for Human-AI Coordination](https://arxiv.org/abs/1910.05789) by Micah Carroll, Rohin Shah, Mark K. Ho, Thomas L. Griffiths, Sanjit A. Seshia, Pieter Abbeel, Anca Dragan. NeurIPS 2019.
* [Multi-Agent Adversarial Inverse Reinforcement Learning](https://arxiv.org/abs/1907.13220) by Lantao Yu, Jiaming Song, Stefano Ermon. ICML 2019.
* [Multi-Agent Generative Adversarial Imitation Learning](https://papers.nips.cc/paper/7975-multi-agent-generative-adversarial-imitation-learning) by Jiaming Song, Hongyu Ren, Dorsa Sadigh, Stefano Ermon. NeurIPS 2018.
* [Cooperative inverse reinforcement learning](http://papers.nips.cc/paper/6420-cooperative-inverse-reinforcement-learning.pdf) by Hadfield-Menell D, Russell S J, Abbeel P, et al. NIPS, 2016.
* [Comparison of Multi-agent and Single-agent Inverse Learning on a Simulated Soccer Example](https://arxiv.org/pdf/1403.6822.pdf) by Lin X, Beling P A, Cogill R. arXiv, 2014.
* [Multi-agent inverse reinforcement learning for zero-sum games](https://arxiv.org/pdf/1403.6508.pdf) by Lin X, Beling P A, Cogill R. arXiv, 2014.
* [Multi-robot inverse reinforcement learning under occlusion with interactions](http://aamas2014.lip6.fr/proceedings/aamas/p173.pdf) by Bogert K, Doshi P. AAMAS, 2014.
* [Multi-agent inverse reinforcement learning](http://homes.soic.indiana.edu/natarasr/Papers/mairl.pdf) by Natarajan S, Kunapuli G, Judah K, et al. ICMLA, 2010.

### Meta Learning
* [Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environments](https://arxiv.org/pdf/1710.03641.pdf) by l-Shedivat, M. 2018.


### Application
* [MuZero with Self-competition for Rate Control in VP9 Video Compression](https://arxiv.org/abs/2202.06626) by Amol Mandhane, Anton Zhernov, Maribeth Rauh, Chenjie Gu, et al. arXiv 2022.
* [MAgent: A Many-Agent Reinforcement Learning Platform for Artificial Collective Intelligence](https://arxiv.org/pdf/1712.00600.pdf) by Zheng L et al. NIPS 2017 & AAAI 2018 Demo. ([Github Page](https://github.com/geek-ai/MAgent))
* [Collaborative Deep Reinforcement Learning for Joint Object Search](https://arxiv.org/pdf/1702.05573.pdf) by Kong X, Xin B, Wang Y, et al. arXiv, 2017.
* [Multi-Agent Stochastic Simulation of Occupants for Building Simulation](http://www.ibpsa.org/proceedings/BS2017/BS2017_051.pdf) by Chapman J, Siebers P, Darren R. Building Simulation, 2017.
* [Extending No-MASS: Multi-Agent Stochastic Simulation for Demand Response of residential appliances](http://www.ibpsa.org/proceedings/BS2017/BS2017_056.pdf) by Sancho-Tomás A, Chapman J, Sumner M, Darren R. Building Simulation, 2017.
* [Safe, Multi-Agent, Reinforcement Learning for Autonomous Driving](https://arxiv.org/pdf/1610.03295.pdf) by Shalev-Shwartz S, Shammah S, Shashua A. arXiv, 2016.
* [Applying multi-agent reinforcement learning to watershed management](https://www.researchgate.net/profile/Karl_Mason/publication/299416955_Applying_Multi-Agent_Reinforcement_Learning_to_Watershed_Management/links/56f545b908ae95e8b6d1d3ff.pdf) by Mason, Karl, et al. Proceedings of the Adaptive and Learning Agents workshop at AAMAS, 2016.
* [Crowd Simulation Via Multi-Agent Reinforcement Learning](http://www.aaai.org/ocs/index.php/AIIDE/AIIDE10/paper/viewFile/2112/2550) by Torrey L. AAAI, 2010.
* [Traffic light control by multiagent reinforcement learning systems](https://pdfs.semanticscholar.org/61bc/b98b7ae3df894f4f72aba3d145bd48ca2cd5.pdf) by Bakker, Bram, et al. Interactive Collaborative Information Systems, 2010.
* [Multiagent reinforcement learning for urban traffic control using coordination graphs](https://staff.science.uva.nl/s.a.whiteson/pubs/kuyerecml08.pdf) by Kuyer, Lior, et al. oint European Conference on Machine Learning and Knowledge Discovery in Databases, 2008.
* [A multi-agent Q-learning framework for optimizing stock trading systems](https://www.researchgate.net/publication/221465347_A_Multi-agent_Q-learning_Framework_for_Optimizing_Stock_Trading_Systems) by Lee J W, Jangmin O. DEXA, 2002.
* [Multi-agent reinforcement learning for traffic light control](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=422747CB9AF552CF1C4E455220E3F96F?doi=10.1.1.32.9887&rep=rep1&type=pdf) by Wiering, Marco. ICML. 2000.


### Networked MARL
* [QD-Learning: A Collaborative Distributed Strategy for Multi-Agent Reinforcement Learning Through Consensus Innovations](https://ieeexplore.ieee.org/document/6415291) by Kar, Soummya and Moura, José M. F. and Poor, H. Vincent. IEEE Transactions on Signal Processing 2013.
* [Fully Decentralized Multi-Agent Reinforcement Learning with Networked Agents](https://proceedings.mlr.press/v80/zhang18n.html) by Kaiqing Zhang, Zhuoran Yang, Han Liu, Tong Zhang, Tamer Basar. ICML 2018.
* [Value Propagation for Decentralized Networked Deep Multi-agent Reinforcement Learning](https://proceedings.neurips.cc/paper/2019/hash/8a0e1141fd37fa5b98d5bb769ba1a7cc-Abstract.html) by Chao Qu, Shie Mannor, Huan Xu, Yuan Qi, Le Song, Junwu Xiong. NIPS 2019.
* [Multi-agent Reinforcement Learning for Networked System Control](https://arxiv.org/abs/2004.01339) by Tianshu Chu, Sandeep Chinchali, Sachin Katti. ICLR 2020.
* [F2A2: Flexible fully-decentralized approximate actor-critic for cooperative multi-agent reinforcement learning](https://arxiv.org/abs/2004.11145) by Wenhao Li, Bo Jin, Xiangfeng Wang, Junchi Yan, Hongyuan Zha. arXiv 2020.
* [Scalable Reinforcement Learning of Localized Policies for Multi-Agent Networked Systems](https://proceedings.mlr.press/v120/qu20a.html) by Guannan Qu, Adam Wierman, Na Li. L4DC 2020.
* [Finite-Sample Analysis For Decentralized Batch Multi-Agent Reinforcement Learning With Networked Agents](https://ieeexplore.ieee.org/abstract/document/9314079) by Zhang, Kaiqing and Yang, Zhuoran and Liu, Han and Zhang, Tong and Başar, Tamer. TAC 2021.


