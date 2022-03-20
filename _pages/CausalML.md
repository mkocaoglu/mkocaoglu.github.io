---
layout: archive
permalink: /CausalML/
title: "CausalML Lab"
author_profile: true
comments: false
redirect_from: 
  - "/CausalML"
  - "/CausalML.html"
  - "/causalML.html"
  - "/causalML"
---
{% include base_path %}

# Projects
Our group's research is focused on developing fundamental algorithms for causal discovery and inference from data. Some threads we focus on are as follows:

## *Information Theoretic Causal Discovery from Observational Data*
We would like to extend the limits of the existing causal discovery algorithms from observational data. We establish connections with information theory and develop efficient algorithms for causal structure discovery using these connections.  
### Related publications:
4. S. Compton, M. Kocaoglu, Kristjan Greenewald, Dmitriy Katz, "[Entropic Causal Inference: Identifiability and Finite Sample Results](https://proceedings.neurips.cc/paper/2020/hash/a979ca2444b34449a2c80b012749e9cd-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.  
3. M. Kocaoglu, S. Shakkottai, A. G. Dimakis, C. Caramanis, S. Vishwanath, "[Applications of Common Entropy for Causal Inference](https://proceedings.neurips.cc/paper/2020/hash/cae7115f44837c806c9b23ed00a1a28a-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.
2. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, B. Hassibi, "[Entropic Causality and Greedy Minimum Entropy Coupling](https://ieeexplore.ieee.org/document/8006772)," in Proc. of **ISIT'17**, 2017.  
1. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, B. Hassibi, "[Entropic Causal Inference](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14218)," in Proc. of **AAAI'17**, San Francisco, USA, Feb. 2017.  

## *Experimental Design for Causal Discovery*
In many settings, further experimentation is possible in order to aid with causal structure discovery. We seek out methods to be as efficient as possible with these experimental designs. Efficiency can mean different things in different contexts, for example, using the smallest possible number of experiments or minimizing an arbitrary modular cost function. 
### Related publications
8. C. Squires, S. Magliacane, K. Greenewald, D. Katz, M. Kocaoglu, K. Shanmugam, "[Active Structure Learning of Causal DAGs via Directed Clique Trees](https://proceedings.neurips.cc/paper/2020/hash/f57bd0a58e953e5c43cd4a4e5af46138-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.  
7. K. Greenewald, D. Katz, K. Shanmugam, S. Magliacane, M. Kocaoglu, E. B. Adsera, G. Bresler, “[Sample Efficient Active Learning of Causal Trees](https://papers.nips.cc/paper/2019/hash/5ee5605917626676f6a285fa4c10f7b0-Abstract.html),” in Proc. of **NeurIPS'19**, Vancouver, Canada, Dec. 2019. 
6. E. Lindgren, M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Experimental Design for Cost-Aware Learning of Causal Graphs](http://papers.neurips.cc/paper/7774-experimental-design-for-cost-aware-learning-of-causal-graphs)" in Proc. of **NeurIPS'18**, Montreal, Canada, Dec. 2018.  
5. E. Lindgren, M. Kocaoglu, A. G. Dimakis, S. Vishwanath, “[Submodularity and Minimum Cost Intervention Design for Learning Causal Graphs](http://www.discml.cc/),” in **DISCML’17 Workshop in NIPS’17**, Dec. 2017.  
8. M. Kocaoglu, K. Shanmugam, E. Bareinboim, "[Experimental Design for Learning Causal Graphs with Latent Variables](https://papers.nips.cc/paper/2017/hash/291d43c696d8c3704cdbe0a72ade5f6c-Abstract.html)," in Proc. of **NeurIPS'17**, 2017.  
9. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Cost-Optimal Learning of Causal Graphs](http://proceedings.mlr.press/v70/kocaoglu17a.html)," in Proc. of **ICML'17**, 2017.  
10. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Learning Causal Graphs with Constraints](https://drive.google.com/file/d/0B6FCKgrwBmezQkZzVHZOLS1STkU)," in **NeurIPS'16 Workshop**: What If? Inference and Learning of Hypothetical and Counterfactual Interventions in Complex Systems, Barcelona, Spain, Dec. 2016.  
11. K. Shanmugam, M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Learning Causal Graphs with Small Interventions](https://proceedings.neurips.cc/paper/2015/hash/b865367fc4c0845c0682bd466e6ebf4c-Abstract.html)," in Proc. of **NeurIPS'15**, Montreal, Canada, Dec. 2015.  

## *Causal Discovery from Interventional Data*
Causal discovery from interventional data is the golden standard where we can get away with the least amount of assumptions. However one challenge today is that interventions are expensive and we need to make best use of the available interventional data. Especially for large-scale systems, learning the causal structure exhaustively requires too many experiments. We focus on distilling as much information as possible from a given collection of interventional datasets. 
### Related publications
2. A. Jaber, M. Kocaoglu, K. Shanmugam, E. Bareinboim, "[Causal Discovery from Soft Interventions with Unknown Targets: Characterization and Learning](https://proceedings.neurips.cc/paper/2020/hash/6cd9313ed34ef58bad3fdd504355e72c-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.  
1. M. Kocaoglu\*, A. Jaber\*, K. Shanmugam\*, E. Bareinboim, “[Characterization and Learning of Causal Graphs with Latent Variables from Soft Interventions](https://docs.google.com/viewer?url=https://github.com/mkocaoglu/mkocaoglu.github.io/raw/master/files/NeurIPS_19__Characterization_and_Learning_of_Causal_Graphs_with_Latent_Variables_from_Soft_Interventions.pdf),” in Proc. of **NeurIPS'19**, Vancouver, Canada, Dec. 2019.  

## *Applications of Causality in Machine Learning*
We explore where causal inference and discovery could benefit the current machine learning methods. 
### Related publications
3. K. Ahuja, P. Sattigeri, K. Shanmugam, D. Wei, K. N. Ramamurthy, M. Kocaoglu, "[Conditionally Independent Data Generation](https://www.auai.org/uai2021/pdf/uai2021.768.pdf)", in Proc. of UAI'21, 2021.  
2. M. Kocaoglu\*, C. Snyder\*, A. G. Dimakis, S. Vishwanath, "[CausalGAN: Learning Causal Implicit Generative Models with Adversarial Training](https://openreview.net/forum?id=BJE-4xW0W)," in Proc. of **ICLR'18**, Vancouver, Canada,  May 2018.  
1. R. Sen, K. Shanmugam, M. Kocaoglu, A. G. Dimakis, S. Shakkottai, "[Contextual Bandits with Latent Confounders: An NMF Approach](http://proceedings.mlr.press/v54/sen17a.html)," in Proc. of **AISTATS'17**, 2017.  

<br/>

# Current Members
## PhD Students
- Kenneth Lee [📄](https://kenneth-lee-ch.github.io/)
- Yifan Zhao  
- Md. Musfiqur Rahman [📄](https://sites.google.com/view/musfiqshohan/)

## MS Students
- Kushagra Kapoor

# Acknowledgement
Our lab is currently supported by funding from Adobe Research. 
