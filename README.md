# RLCO-Papers

Reinforcement Learning based combinatorial optimization (**RLCO**) is a very interesting research area. 
Combinatorial Optimization Problems include: Travelling Salesman Problem (**TSP**), Vehicle Routing Problem (**VRP**), Orienteering Problem, Knapsack Problem, Maximal Independent Set (**MIS**), Maximum Cut (**MC**), Minimum Vertex Cover (**MVC**), Maximal Clique (**MC**), Intger Linear Programming (**ILP**), Network Optimization (Routing), Bin Packing Problem, Graph Partioning, **EDA** problems. Most of them are NP-hard or NP-complete. 
Combinatorial Problems can traditionally be solved by: exact method, heuristic method (genetic algorithm, simulated annealing), etc. Recently, better learning-based solvers are coming out. 

This is a collection of resaerch & application papers of RLCO. Papers are sorted by time and categories. Some related supervised learning papers are also listed as a reference.


The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact [Haiguang Liao]  (Email: haiguanl [AT] andrew.cmu.edu). Feedbacks on any mistakes on the repo are also welcomed

## Research Papers:
Papers are catgorized based on the solution approahces and ordered in time sequence:
### 1. Policy RL + (GNN)
* [Reinforcement Learning for Integer Programming- Learning to Cut](https://proceedings.icml.cc/static/paper_files/icml/2020/943-Paper.pdf) Yunhao Tang et al. ICML 2020. (Columbia University)
* [Learning to Perform Local Rewriting for Combinatorial Optimization](https://arxiv.org/pdf/1810.00337.pdf) Xinyun Chen, Yuandong Tian. NeurIPS 2019 (UC Berkeley & Facebook AI Research)
* [Attention, Learn to Solve Routing Problems!](https://arxiv.org/pdf/1803.08475.pdf?source=post_page---------------------------) Max Welling et al. ICLR 2019. (Architecture: Graph Attention Network)
* [Learning to Solve Combinatorial Optimization
Problems on Real-World Graphs in Linear Time](https://arxiv.org/pdf/2006.03750.pdf) Iddo Drori et al. 2020
* [Reinforcement Learning Driven Heuristic Optimization](https://arxiv.org/pdf/1906.06639.pdf) Qingpeng Cai, Azalia Mirhoseini et al. DRL4KDD 2019 (Tsinghua University, Google Brain, Google AI)


### 2. Value RL + (GNN)
* [Deep Reinforcement Learning meets Graph Neural
Networks: exploring a routing optimization use case](https://arxiv.org/pdf/1803.08475.pdf?source=post_page---------------------------) Paul Almasan et al. 2020
* [Learning Combinatorial Optimization Algorithms over Graphs](https://arxiv.org/pdf/1704.01665.pdf) Hanjun Dai, Le Song et al. NeurlIPS 2017 (GaTech) 

### 3. Supervised Learning + Tree Search + Graph Embedding
* [Combinatorial Optimzation with Graph Convolutional Networks and Guided Tree Search](https://papers.nips.cc/paper/7335-combinatorial-optimization-with-graph-convolutional-networks-and-guided-tree-search.pdf) Zhuwen Li et al. NeurlIPS 2017 (Intel)

## Electronic Design Automation (EDA) Application Papers:
EDA is not easy. Some problems in EDA such as physical design (**floorplan**, **placement**, **routing**, etc.) can be reduced to combinatorial optimization problems. Thus, some of them are solved with RLCO.

* [Attention Routing: track-assignment detailed routing using attention-based reinforcement learning](https://arxiv.org/pdf/2004.09473.pdf) Haiguang Liao et al. 2020 (CMU & Cadence)
* [Chip Placement with Deep Reinforcement Learning](https://arxiv.org/pdf/2004.10746.pdf) Azalia Mirhoseini et al. 2020 (Google)
* [Placement Optimization with Deep Reinforcement Learning](https://dl.acm.org/doi/pdf/10.1145/3372780.3378174
) Anna Goldie, Azalia Mirhoseini ISPD 2020 (Google Brain) 
 * [Placeto: Learning Generalizable Device Placement
Algorithms for Distributed Machine Learning](https://arxiv.org/pdf/1906.08879.pdf) Ravichandra Addanki et al. 2019 (MIT CSAIL)
* [GDP: Generalized Device Placement for Dataflow Graphs](https://arxiv.org/pdf/1910.01578.pdf) Yanqi Zhou et al. 2019 (Google Brain)
* [A Deep Reinforcement Learning Approach for Global Routing](https://arxiv.org/pdf/1906.08809.pdf) Haiguang Liao et al. 2019 (CMU)
* [A Hierarchical Model for Device Placement](https://arxiv.org/pdf/1906.06639.pdf) Azalia Mirhoseini et al. ICLR 2018 (Google)
* [Device Placement Optimization with Reinforcement Learning](https://arxiv.org/pdf/1706.04972.pdf) Azalia Mirhoseini et al. ICML 2017 (Google Brain)
 

