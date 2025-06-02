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
<div style="display: flex; align-items: flex-start; gap: 0;">
<div style="flex: 1;">
Causal reasoning is essential for artificial intelligence and machine learning. In CausalML lab, we develop new theoretical results that give us insights about fundamental causal discovery and inference problems, and develop novel algorithms based on these insights. Our research can be broadly categorized into multiple pillars:
</div>
<div style="padding: 0 0 0 30px;">
<img src="/images/lablogo.png" width="140">
</div>
</div>
<div style="margin-bottom: -40px;"></div>
* [High-dimensional Causal Inference with Deep Generative Models](#high-dim)
{: style="margin-left: 40px"}
* [Causal Methods for Computer Security](#security)
{: style="margin-left: 40px"}
* [Causal Bandit Algorithms](#bandits)
{: style="margin-left: 40px"}
* [Fundamentals of Causal Discovery](#discovery)
{: style="margin-left: 40px"}
* [Causal Machine Learning](#causal-ml)
{: style="margin-left: 40px"}
* [Practical and Approximate Causal Reasoning via Information-theoretic Methods](#entropic)
{: style="margin-left: 40px"}

The code repositories for accepted papers can be found on our lab's GitHub page at
[https://github.com/CausalML-Lab](https://github.com/CausalML-Lab).
# Current Members
 
## *PhD Students*
- Md Musfiqur Rahman [📄](https://sites.google.com/view/musfiqshohan/)
- Kenneth Lee [📄](https://kenneth-lee-ch.github.io/)
- Ziwei Jiang [📄](https://ziwei-jiang.github.io/)
- Shanyun Gao [📄](https://sites.google.com/view/shanyungao/home)
- Qasim Elahi [📄](https://qasimelahi.github.io/QasimElahi/)
- Zihan Zhou [📄](https://sites.google.com/view/zihan-zhou/home)

# Projects
Our group's research is focused on developing fundamental algorithms for causal discovery and inference from data, and exploring the connections between causality and machine learning, information theory, graph theory, deep learning, online learning. Some threads we focus on are as follows. 

<a name="high-dim"></a>
## *High-dimensional Causal Inference with Deep Generative Models*
We are interested in leveraging the representation capabilities of deep neural networks to enable sampling from causal queries in the presence of high-dimensional variables such as images. 

### Related Publications
4. M. M. Rahman, M. Kocaoglu, "FeDCM: Federated Learning of Deep Causal Generative Models," in Proc. of **UAI'25**, Rio de Janeiro, Brazil, July 2025.
3. M. M. Rahman\*, M. Jordan\*, M. Kocaoglu, "[Conditional Generative Models are Sufficient to Sample from Any Causal Effect Estimand](https://arxiv.org/abs/2402.07419)," in Proc. of **NeurIPS'24**, Vancouver, Canada, Dec. 2024.
2. M. M. Rahman, M. Kocaoglu, "[Modular Learning of Deep Causal Generative Models for High-dimensional Causal Inference](https://arxiv.org/abs/2401.01426)," in Proc. of **ICML'24**, Vienna, Austria, July 2024.
1. M. Kocaoglu\*, C. Snyder\*, A. G. Dimakis, S. Vishwanath, "[CausalGAN: Learning Causal Implicit Generative Models with Adversarial Training](https://openreview.net/forum?id=BJE-4xW0W)," in Proc. of **ICLR'18**, Vancouver, Canada,  May 2018.  

<a name="security"></a>
## *Causal Methods for Computer Security*
We develop principled methods for root-cause analysis and change point detection. 
4. A. Ikram, K. Lee, S. Agarwal, S. K. Saini, S. Bagchi, M. Kocaoglu, "Root Cause Analysis of Failures from Partial Causal Structures," in Proc. of **UAI'25**, Rio de Janeiro, Brazil, July 2025.
3. S. Gao, R. Addanki, T. Yu, R. A. Rossi, M. Kocaoglu, "[Causal Discovery-Driven Change Point Detection in Time Series](https://openreview.net/forum?id=3tV5AtAXk0)," in Proc. of **AISTATS'25**, May 2025.
2. S. Gao, R. Addanki, T. Yu, R. A. Rossi, M. Kocaoglu, “Causal Discovery in Semi-Stationary Time Series,” in Proc. of **NeurIPS'23**, New Orleans, LA, USA, Dec. 2023.
1. M. A. Ikram, S. Chakraborty, S. Mitra, S. Saini, S. Bagchi, M. Kocaoglu, "[Root Cause Analysis of Failures in Microservices through Causal Discovery](https://openreview.net/pdf?id=weoLjoYFvXY)," in Proc. of **NeurIPS'22**, Dec. 2022.


<a name="bandits"></a>
## *Causal Bandit Algorithms*
We explore the fundamentals of online learning from a causal perspective and develop algorithms that balance exploration and exploitation to maximize a reward signal.
3. M. Q. Elahi, M. Ghasemi, M. Kocaoglu, "Partial Structure Discovery is Sufficient for No-regret Learning in Causal Bandits," in Proc. of **NeurIPS’24**, Vancouver, Canada, Dec. 2024.
2. L. Wei, M. Q. Elahi, M. Ghasemi, M. Kocaoglu, “Approximate Allocation Matching for Structural Causal Bandits with Unobserved Confounders,” in Proc. of **NeurIPS’23**, New Orleans, LA, USA, Dec. 2023.
1. R. Sen, K. Shanmugam, M. Kocaoglu, A. G. Dimakis, S. Shakkottai, "[Contextual Bandits with Latent Confounders: An NMF Approach](http://proceedings.mlr.press/v54/sen17a.html)," in Proc. of **AISTATS'17**, 2017.  


<a name="discovery"></a>
## *Fundamentals of Causal Discovery*
We explore the limits of causal knowledge that can be extracted from data under well-defined assumptions and develop causal discovery algorithms to achieve these limits. 
14. K. Lee, B. Ribeiro, M. Kocaoglu, "Constraint-based Causal Discovery from a Collection of Conditioning Sets," in Proc. of **UAI'25**, Rio de Janeiro, Brazil, July 2025.
13. Z. Zhou, M. Q. Elahi, M. Kocaoglu, "Sample Efficient Bayesian Learning of Causal Graphs from Interventions," in Proc. of **NeurIPS’24**, Vancouver, Canada, Dec. 2024.
12. M. Kocaoglu, "Characterization and Learning of Causal Graphs with Small Conditioning Sets," in Proc. of **NeurIPS'23**, New Orleans, LA, 2023.
11. A. Shah, K. Shanmugam, M. Kocaoglu, "Front-door Adjustment Beyond Markov Equivalence with Limited Graph Knowledge," in Proc. of **NeurIPS'23**, New Orleans, LA, USA, Dec. 2023.
10. C. Squires, S. Magliacane, K. Greenewald, D. Katz, M. Kocaoglu, K. Shanmugam, "[Active Structure Learning of Causal DAGs via Directed Clique Trees](https://proceedings.neurips.cc/paper/2020/hash/f57bd0a58e953e5c43cd4a4e5af46138-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.  
9. K. Greenewald, D. Katz, K. Shanmugam, S. Magliacane, M. Kocaoglu, E. B. Adsera, G. Bresler, “[Sample Efficient Active Learning of Causal Trees](https://papers.nips.cc/paper/2019/hash/5ee5605917626676f6a285fa4c10f7b0-Abstract.html),” in Proc. of **NeurIPS'19**, Vancouver, Canada, Dec. 2019.
8. A. Jaber, M. Kocaoglu, K. Shanmugam, E. Bareinboim, "[Causal Discovery from Soft Interventions with Unknown Targets: Characterization and Learning](https://proceedings.neurips.cc/paper/2020/hash/6cd9313ed34ef58bad3fdd504355e72c-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.  
7. M. Kocaoglu\*, A. Jaber\*, K. Shanmugam\*, E. Bareinboim, “[Characterization and Learning of Causal Graphs with Latent Variables from Soft Interventions](https://docs.google.com/viewer?url=https://github.com/mkocaoglu/mkocaoglu.github.io/raw/master/files/NeurIPS_19__Characterization_and_Learning_of_Causal_Graphs_with_Latent_Variables_from_Soft_Interventions.pdf),” in Proc. of **NeurIPS'19**, Vancouver, Canada, Dec. 2019.
6. E. Lindgren, M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Experimental Design for Cost-Aware Learning of Causal Graphs](http://papers.neurips.cc/paper/7774-experimental-design-for-cost-aware-learning-of-causal-graphs)" in Proc. of **NeurIPS'18**, Montreal, Canada, Dec. 2018.  
5. E. Lindgren, M. Kocaoglu, A. G. Dimakis, S. Vishwanath, “[Submodularity and Minimum Cost Intervention Design for Learning Causal Graphs](http://www.discml.cc/),” in **DISCML’17 Workshop in NIPS’17**, Dec. 2017.  
4. M. Kocaoglu, K. Shanmugam, E. Bareinboim, "[Experimental Design for Learning Causal Graphs with Latent Variables](https://papers.nips.cc/paper/2017/hash/291d43c696d8c3704cdbe0a72ade5f6c-Abstract.html)," in Proc. of **NeurIPS'17**, 2017.  
3. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Cost-Optimal Learning of Causal Graphs](http://proceedings.mlr.press/v70/kocaoglu17a.html)," in Proc. of **ICML'17**, 2017.  
2. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Learning Causal Graphs with Constraints](https://drive.google.com/file/d/0B6FCKgrwBmezQkZzVHZOLS1STkU)," in **NeurIPS'16 Workshop**: What If? Inference and Learning of Hypothetical and Counterfactual Interventions in Complex Systems, Barcelona, Spain, Dec. 2016.  
1. K. Shanmugam, M. Kocaoglu, A. G. Dimakis, S. Vishwanath, "[Learning Causal Graphs with Small Interventions](https://proceedings.neurips.cc/paper/2015/hash/b865367fc4c0845c0682bd466e6ebf4c-Abstract.html)," in Proc. of **NeurIPS'15**, Montreal, Canada, Dec. 2015.  

<a name="causal-ml"></a>
## *Causal Machine Learning*
We explore ways in which causal inference and discovery can help more robust and practical machine learning solutions. 
### Related publications
5. Z. Zhou, T. Liu, R. Bai, J. Gao, M. Kocaoglu, D. I. Inouye, "Counterfactual Fairness by Combining Factual and Counterfactual Predictions," in Proc. of **NeurIPS’24**, Vancouver, Canada, Dec. 2024.
4. M. Q. Elahi, L. Wei, M. Kocaoglu, M. Ghasemi, "Adaptive Online Experimental Design for Causal Discovery," in Proc. of **ICML'24**, Austria, Vienna, July 2024.
3. Sean Kulinski, Zeyu Zhou, Ruqi Bai, Murat Kocaoglu, David I. Inouye [Towards Characterizing Domain Counterfactuals for Invertible Latent Causal Models](https://openreview.net/forum?id=v1VvCWJAL8)" to appear in Proc. of **ICLR'24**, Vienna, Austria, May 2024.
2. K. Lee, M. M. Rahman, M. Kocaoglu, "[Finding Invariant Predictors Efficiently via Causal Structure](https://proceedings.mlr.press/v216/lee23a.html)," in Proc. of **UAI'23**, Pittsburgh, PA, USA, Aug. 2023.
1. K. Ahuja, P. Sattigeri, K. Shanmugam, D. Wei, K. N. Ramamurthy, M. Kocaoglu, "[Conditionally Independent Data Generation](https://www.auai.org/uai2021/pdf/uai2021.768.pdf)", in Proc. of **UAI'21**, 2021.  

<a name="entropic"></a>
## *Practical and Approximate Causal Reasoning via Information-theoretic Methods*
Information-theoretic tools provide us with ways to go beyond the boundaries of classical causal reasoning algorithms and make approximate causal inferences under practical assumptions. 

### Related publications:
8. Z. Jiang, M. Kocaoglu, "Conditional Common Entropy for Instrumental Variable Testing and Partial Identification," in Proc. of **ICML'24**, Vienna, Austria, July 2024.
7. Z. Jiang, L. Wei, M. Kocaoglu, "[Approximate Causal Effect Identification under Weak Confounding](https://openreview.net/pdf?id=iRBKUnIjR2)," in Proc. of **ICML'23**, Honolulu, HI, USA, July 2023.
6. S. Compton, D. Katz, B. Qi, K. Greenewald, M. Kocaoglu, "[Minimum-Entropy Coupling Approximation Guarantees Beyond the Majorization Barrier](https://proceedings.mlr.press/v206/compton23a/compton23a.pdf)," in Proc. of **AISTATS'23**, Valencia, Spain, April 2023.
5. S. Compton, K. Greenewald, D. Katz, M. Kocaoglu, “[Entropic Causal Inference: Graph Identifiability](https://proceedings.mlr.press/v162/compton22a.html)”, in Proc. of **ICML’22**, July 2022.
4. S. Compton, M. Kocaoglu, Kristjan Greenewald, Dmitriy Katz, "[Entropic Causal Inference: Identifiability and Finite Sample Results](https://proceedings.neurips.cc/paper/2020/hash/a979ca2444b34449a2c80b012749e9cd-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.  
3. M. Kocaoglu, S. Shakkottai, A. G. Dimakis, C. Caramanis, S. Vishwanath, "[Applications of Common Entropy for Causal Inference](https://proceedings.neurips.cc/paper/2020/hash/cae7115f44837c806c9b23ed00a1a28a-Abstract.html)," in Proc. of **NeurIPS'20**, Online, Dec. 2020.
2. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, B. Hassibi, "[Entropic Causality and Greedy Minimum Entropy Coupling](https://ieeexplore.ieee.org/document/8006772)," in Proc. of **ISIT'17**, 2017.  
1. M. Kocaoglu, A. G. Dimakis, S. Vishwanath, B. Hassibi, "[Entropic Causal Inference](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14218)," in Proc. of **AAAI'17**, San Francisco, USA, Feb. 2017.  

<br/>

# Past Members

## PostDoc Researchers
- Lai Wei, *August 2022 - August 2023* [📄](https://openreview.net/profile?id=~Lai_Wei5) 
  
## Visiting Researcher
- Suyeong Park, *July - August 2022* [📄](https://euphoria0-0.github.io/tabs/about/)

<br/>

# Acknowledgement
Our lab is currently supported by the National Science Foundation (NSF), Adobe Research, Amazon, and Google. 
