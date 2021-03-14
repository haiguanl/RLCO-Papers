# RLCO-Papers

Reinforcement Learning based combinatorial optimization (**RLCO**) is a very interesting research area. 
Combinatorial Optimization Problems include: Travelling Salesman Problem (**TSP**), Single-Source Shortest Paths (**SSP**), Minimum Spanning Tree (**MST**), Vehicle Routing Problem (**VRP**), Orienteering Problem, Knapsack Problem, Maximal Independent Set (**MIS**), Maximum Cut (**MC**), Minimum Vertex Cover (**MVC**), Maximal Clique (**MC**), Integer Linear Programming (**ILP**), Network Optimization (Routing), Graph Coloring Problem (**GCP**), Bin Packing Problem, Graph Partitioning, **EDA** problems. Most of them are NP-hard or NP-complete. 
Combinatorial Problems can traditionally be solved by: exact method, heuristic method (genetic algorithm, simulated annealing), etc. Recently, better learning-based solvers are coming out. 

This is a collection of resaerch & application papers of RLCO. Papers are sorted by time and categories. Some related supervised learning papers are also listed as a reference.


The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact [Haiguang Liao]  (Email: haiguanl [AT] andrew.cmu.edu). Feedbacks on any mistakes on the repo are also welcomed

## Review Papers:
* [Reinforcement Learning for Combinatorial Optimization: A Survey
](https://arxiv.org/pdf/2003.03600.pdf) Nina Mazyavkina et al. (Skolkovo Institute of Science and Technology, Russia)

## Research Papers:
Papers are catgorized based on the solution approahces and ordered in time sequence:
### 1. Policy RL + (GNN)
* [POMO: Policy Optimization with Multiple Optima for Reinforcement Learning](https://arxiv.org/pdf/2010.16011.pdf) Yeong-Dae Kwon et al. NeurIPS 2020 (Samsung SDS)
* [Reinforcement Learning for Integer Programming- Learning to Cut](https://proceedings.icml.cc/static/paper_files/icml/2020/943-Paper.pdf) Yunhao Tang et al. ICML 2020 (Columbia University)
* [Learning to Perform Local Rewriting for Combinatorial Optimization](https://arxiv.org/pdf/1810.00337.pdf) Xinyun Chen, Yuandong Tian. NeurIPS 2019 (UC Berkeley & Facebook AI Research)
* [Attention, Learn to Solve Routing Problems!](https://arxiv.org/pdf/1803.08475.pdf?source=post_page---------------------------) Max Welling et al. ICLR 2019 (Architecture: Graph Attention Network)
* [Learning to Solve Combinatorial Optimization
Problems on Real-World Graphs in Linear Time](https://arxiv.org/pdf/2006.03750.pdf) Iddo Drori et al. 2020 (Columbia University, Cornell University)
* [Reinforcement Learning Driven Heuristic Optimization](https://arxiv.org/pdf/1906.06639.pdf) Qingpeng Cai, Azalia Mirhoseini et al. DRL4KDD 2019 (Tsinghua University, Google Brain, Google AI)
* [Neural Combinatorial Optimization with Reinforcement Learning](https://arxiv.org/pdf/1611.09940.pdf) Irwan Bello et al. ICLR 2017 (Google Brain)


### 2. Value RL + (GNN)
* [Deep Reinforcement Learning meets Graph Neural
Networks: exploring a routing optimization use case](https://arxiv.org/pdf/1803.08475.pdf?source=post_page---------------------------) Paul Almasan et al. 2020
* [Learning Combinatorial Optimization Algorithms over Graphs](https://arxiv.org/pdf/1704.01665.pdf) Hanjun Dai, Le Song et al. NeurlIPS 2017 (GaTech) 

### 3. Supervised Learning + Tree Search + Graph Embedding
* [Combinatorial Optimzation with Graph Convolutional Networks and Guided Tree Search](https://papers.nips.cc/paper/7335-combinatorial-optimization-with-graph-convolutional-networks-and-guided-tree-search.pdf) Zhuwen Li et al. NeurlIPS 2017 (Intel)

## Application Papers:
Papers are catgorized based on the application domains and ordered in time sequence:
### 1. Electronic Design Automation (EDA)
EDA is not easy. Some problems in EDA such as physical design (**floorplan**, **placement**, **routing**, etc.) can be formulated as combinatorial optimization problems. Thus, some of them are solved with RLCO.
* [Track-Assignment Detailed Routing Using Attention-based Policy Model With Supervision](https://arxiv.org/pdf/2010.13702.pdf) Haiguang Liao et al. 2020 (CMU & Cadence)
* [AutoCkt: Deep Reinforcement Learning of Analog Circuit Designs
](https://arxiv.org/pdf/2001.01808.pdf) Keertana Settaluri et al. 2020 (UC Berkeley)
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
 
 ### 2. Path Planning (Routing)
 RL has been extensively applied to robotic path planning, the papers listed here are only a tiny subset of those we think relevent to RLCO. 
* [Multi-Agent Routing Value Iteration Network](https://arxiv.org/pdf/2007.05096.pdf) Quinlan Sykora et al. PMLR 2020 (Uber)
 * [Value Iteration Networks](https://arxiv.org/pdf/1602.02867.pdf) (Code: https://github.com/kentsommer/pytorch-value-iteration-networks) Aviv Tamar et al. NeurlIPS 2016 (UC Berkeley)

 ### 3. Resource Management
 * [Resource Management with Deep Reinforcement Learning](https://www.cl.cam.ac.uk/~ey204/teaching/ACS/R244_2018_2019/papers/mao_HOTNETS_2016.pdf) Hongzi Mao et al. ACM_HotNets 2016 (MIT & Microsoft Research)

 
 ## Related Papers:
### 1. MLCO (Machine Learning for Combinatorial Optimization)
* [Machine learning for combinatorial optimization: a methodological tour d’horizon](https://arxiv.org/pdf/1811.06128.pdf) Yoshua Bengio et al. 2020 (Universit´e de Montr´eal, etc.)
* [Learning Combinatorial Optimization on Graphs: A Survey with Applications to Networking](https://arxiv.org/pdf/2005.11081.pdf) Natalia Vesselinova et al. 2020
### 2. ILCO (Imitation for Combinatorial Optimization)
* [Exact Combinatorial Optimization
with Graph Convolutional Neural Networks](https://arxiv.org/pdf/1906.01629.pdf) Maxime Gasse et al. NeurlIPS 2019 (Mila, Polytechnique Montréal, etc.)
### 3. GNN and CO
* .[Combinatorial optimization and reasoning with graph neural networks](https://arxiv.org/pdf/2102.09544.pdf)


 ## Relevant Resources:
 ### Frameworks:
 1. PyTorch Geometric [https://arxiv.org/pdf/1903.02428.pdf] (TU Dortmund University)
 2. Deep Graph Library [https://arxiv.org/pdf/1909.01315.pdf] (Amazon Web Services, AWS Shanghai AI Lab, New York University, NYU Shanghai)

 ### Libraries:
 1. Facilate the learning of heuristics for CO problems similar to OpenAI Gym.
 * [OR-Gym](https://arxiv.org/pdf/2008.06319.pdf) (CMU)
 * [OpenGraphGym](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7302566/) 
 2. Facilitate the learning of configuration parameters for CO solvers. 
 * [MIPLLearn](https://anl-ceeesa.github.io/ MIPLearn.)
 3. Offering a general, extensible framework for implementing and evaluating machine learning-enhanced CO, also based on OpenAI Gym. 
 * [Ecole](https://arxiv.org/pdf/2011.06069.pdf) (Mila, Polytechnique Montréal)
 ### Environments/Problems:
 
 
 
