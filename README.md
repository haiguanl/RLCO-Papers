# RLCO-Papers

Reinforcement Learning based combinatorial optimization (**RLCO**) is a very interesting research area. 
Combinatorial Optimization Problems include: Travelling Salesman Problem (**TSP**), Vehicle Routing Problem (**VRP**), Orienteering Problem, Knapsack Problem, Maximal Independent Set (**MIS**), Maximum Cut (**MC**), Minimum Vertex Cover (**MVC**), Maximal Clique (**MC**), Intger Linear Programming (**ILP**), Routing, **EDA** domain problems. Most of them are NP-hard. 
Combinatorial Problems can traditionally be solved by: exact method, heuristics-based method

This is a collection of resaerch papers of RLCO. Papers are sorted by time and categories. Some related supervised learning papers are also listed as a reference.


The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact [Haiguang Liao]  (Email: haiguanl [AT] andrew.cmu.edu). Feedbacks on any mistakes on the repo are also welcomed

## Research Papers:
Papers are catgorized based on the solution approahces and ordered in time sequence:
### 1. Policy RL
* [Attention, Learn to Solve Routing Problems!](https://arxiv.org/pdf/1803.08475.pdf?source=post_page---------------------------) Max Welling et al. ICLR 2019. (Architecture: Graph Attention Network)

### 2. Value RL
* [Deep Reinforcement Learning meets Graph Neural
Networks: exploring a routing optimization use case](https://arxiv.org/pdf/1803.08475.pdf?source=post_page---------------------------) Paul Almasan et al. 2020.
* [Learning Combinatorial Optimization Algorithms over Graphs](https://arxiv.org/pdf/1704.01665.pdf) Hanjun Dai, Le Song et al. (GaTech) NeurlIPS 2017.

### 3. Supervised Learning + Tree Search + Graph Embedding
* [Combinatorial Optimzation with Graph Convolutional Networks and Guided Tree Search](https://papers.nips.cc/paper/7335-combinatorial-optimization-with-graph-convolutional-networks-and-guided-tree-search.pdf) Zhuwen Li (Intel) et al. NeurlIPS 2017. 

## EDA Application Papers:
Some problems in EDA such as physical design (floorplan, placement, routing, etc.) can be reduced to combinatorial optimization problems. Thus, some of them are solved with RLCO.
 * [Placeto: Learning Generalizable Device Placement
Algorithms for Distributed Machine Learning](https://arxiv.org/pdf/1906.08879.pdf) Ravichandra Addanki et al. 2019 (MIT CSAIL)
* [GDP: Generalized Device Placement for Dataflow Graphs](https://arxiv.org/pdf/1910.01578.pdf) Yanqi Zhou et al. 2019 (Google Brain)
* [Chip Placement with Deep Reinforcement Learning](https://arxiv.org/pdf/2004.10746.pdf) Azalia Mirhoseini et al. 2019 (Google)

