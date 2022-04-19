# awesome-instance-attribution ![Awesome](figures/awesome.svg)
A collection of resources on instance attribution (in deep learning).

Did we miss a relevant resource? Feel free to raise an Issue or create a Pull Request.


## Table of Contents
- [ToDos](#todos)
- [Methods](#methods)
- [Evaluation](#evaluation)
- [Other](#other)


## [ToDos](#content)
- Scout papers for additional resources
- add github links for many papers
- sort papers by some attribute? (e.g. publication data or arxiv date?)
- write short gist for each resource. E.g. what research questions is it about? what are the key insights?

## [Methods](#content)
- **Influential Instances**
    
    Chapter in the Interpretable ML Book by Christoph Molnar.

    [book chapter](https://christophm.github.io/interpretable-ml-book/influential.html)

- **Understanding Black-box Predictions via Influence Functions**:

    Koh and Liang. ICML 2017 (Best Paper)

    [arxiv](https://arxiv.org/abs/1703.04730) [github](https://github.com/kohpangwei/influence-release)


- **Efficient Estimation of Influence of a Training Instance**
    
    Kobayashi et al. SustaiNLP2020

    [arxiv](https://arxiv.org/abs/2012.04207)

- **FastIF: Scalable Influence Functions for Efficient Model Interpretation and Debugging**
    
    Guo et al. EMNLP 2021

    [arxiv](https://arxiv.org/abs/2012.15781) [github](https://github.com/salesforce/fast-influence-functions)

- **Input Similarity from the Neural Network Perspective**
    
    Charpiat et al. NeurIPS 2019

    [arxiv](https://arxiv.org/abs/2102.05262) [github](https://github.com/Lydorn/netsimilarity)

- **RelatIF: Identifying Explanatory Training Examples via Relative Influence**

    Barshan et al. AISTATS 2020

    [arxiv](https://arxiv.org/abs/2003.11630)

- **Representer Point Selection for Explaining Deep Neural Networks**
- 
    Yeh et al. NeurIPS 2018

    [arxiv](https://arxiv.org/abs/1811.09720)

- **Estimating Training Data Influence by Tracing Gradient Descent**
  
    Pruthi et al. NeurIPS 2020

    [arxiv](https://arxiv.org/abs/2002.08484)

- **Scaling Up Influence Functions**

    Schioppa et al. AAAI 2022

    [arxiv](https://arxiv.org/abs/2112.03052) [github](https://github.com/google-research/jax-influence)

- **Interpreting Black Box Predictions using Fisher Kernels**

    Khanna et al. AISTATS 2019

    [arxiv](https://arxiv.org/abs/1810.10118)


## [Evaluation](#content)
- **Evaluation of Similarity-based Explanations**

    Hanawa et al. ICLR 2021
  
    [arxiv](https://arxiv.org/abs/2006.04528)

- **An Empirical Comparison of Instance Attribution Methods for NLP**
    
    Pezeshkpour et al. NAACL 2021

    [arxiv](https://arxiv.org/abs/2104.04128) [github](https://github.com/successar/instance_attributions_NLP)

- **Explaining Black Box Predictions and Unveiling Data Artifacts through Influence Functions**

    Han et al. ACL 2020

    [arxiv](https://arxiv.org/abs/2005.06676)

- **Influence Functions in Deep Learning are Fragile**
    
    Basu et al. ICLR 2021

    [arxiv](https://arxiv.org/abs/2006.14651) 

- **Revisiting Methods for Finding Influential Examples**
    
    K and Søgaard. AAAI 2022
    
    [arxiv](https://arxiv.org/abs/2111.04683)


## [Other](#content)
- **What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation**

    Feldman and Zhang. NeurIPS 2020

    [arxiv](https://arxiv.org/abs/2008.03703)

- **On the Accuracy of Influence Functions for Measuring Group Effects**

    Koh et al.

    [arxiv](https://arxiv.org/abs/1905.13289)

- **Examples are not enough, learn to criticize! Criticism for Interpretability**

    Kim et al. NeurIPS 2016

    [paper](https://papers.nips.cc/paper/2016/hash/5680522b8e2bb01943234bce7bf84534-Abstract.html)

- **Finding Influential Training Samples for Gradient Boosted Decision Trees**

    Sharchilev et al. ICML 2018

    [arxiv](https://arxiv.org/abs/1802.06640)

- **An Empirical Study of Example Forgetting during Deep Neural Network Learnin**

    Toneva et al. ICLR 2019

    [arxiv](https://arxiv.org/abs/1812.05159)


- **Towards Efficient Data Valuation Based on the Shapley Value**

    Jia et al. AISTATS 2019

    [arxiv](https://arxiv.org/abs/1902.10275)

- **Data Cleansing for Models Trained with SGD**

    Hara et al. NeurIPS 2019

    [arxiv](https://arxiv.org/abs/1906.08473)

- **Data Shapley: Equitable Valuation of Data for Machine Learning**

    Ghorbani and Zhou. ICML 2019

    [arxiv](https://arxiv.org/abs/1904.02868) [github](https://github.com/amiratag/DataShapley)

- **This Looks Like That: Deep Learning for Interpretable Image Recognition**

    Chen et al. NeurIPS 2019

    [arxiv](https://arxiv.org/abs/1806.10574)

- **Understanding the Origins of Bias in Word Embeddings**

    Brunet et al. ICML 2019

    [arxiv](https://arxiv.org/abs/1810.03611)

- **Data Valuation using Reinforcement Learning**

    Yoon et al. ICML 2020

    [arxiv](https://arxiv.org/abs/1909.11671)

- **Dataset Cartography: Mapping and Diagnosing Datasets with Training Dynamics**

    Swayamdipta et al. EMNLP 2020

    [arxiv](https://arxiv.org/abs/2009.10795)

- **Identifying Mislabeled Data using the Area Under the Margin Ranking**

    Pleiss et al. NeurIPS 2020

    [arxiv](https://arxiv.org/abs/2001.10528)

- **Towards Faithfully Interpretable NLP Systems: How Should We Define and Evaluate Faithfulness?**

    Jacovi and Goldberg. ACL 2020

    [arxiv](https://arxiv.org/abs/2004.03685)

- **Estimating Example Difficulty Using Variance of Gradients**

    Agarwal et al. WHI Workshop @ICML 2020.

    [arxiv](https://arxiv.org/abs/2008.11600)

- **Does learning require memorization? a short tale about a long tail**

    Feldman. STOC 2020

    [arxiv](https://arxiv.org/abs/1906.05271)

- **Multi-Stage Influence Function**

    Chen et al. NeurIPS 2020

    [arxiv](https://arxiv.org/abs/2007.09081)

- **TREX: Tree-Ensemble Representer-Point Explanations**

    Brophy and Lowd. XXAI Workshop at ICML 2020.

    [arxiv](https://arxiv.org/abs/2009.05530)

- **On Second-Order Group Influence Functions for Black-Box Predictions**

    Basu et al. ICML 2020

    [arxiv](https://arxiv.org/abs/1911.00418)

- **On Sample Based Explanation Methods for NLP: Faithfulness, Efficiency and Semantic Evaluation**

    Zhang et al. ACL 2021

    [arxiv](https://arxiv.org/abs/2106.04753)

- **Influence Estimation for Generative Adversarial Networks**

    Terashita et al. ICLR 2021

    [arxiv](https://arxiv.org/abs/2101.08367)

- **Representer Point Selection via Local Jacobian Expansion for Post-hoc Classifier Explanation of Deep Neural Networks and Ensemble Models**

    Sui et al. NeurIPS 2021

    [paper](https://proceedings.neurips.cc//paper/2021/hash/c460dc0f18fc309ac07306a4a55d2fd6-Abstract.html) [github](https://github.com/echoyi/RPS_LJE)

- **Deep Learning on a Data Diet: Finding Important Examples Early in Training**

    Paul et al. NeurIPS 2021

    [arxiv](https://arxiv.org/abs/2107.07075)

- **Understanding Instance-based Interpretability of Variational Auto-Encoders**

    Kong and Chaudhuri. NeurIPS 2021

    [arxiv](https://arxiv.org/abs/2105.14203)

- **Characterizing Structural Regularities of Labeled Data in Overparameterized Models**

    Jiang et al. ICML 2021

    [arxiv](https://arxiv.org/abs/2002.03206)

- **Estimating informativeness of samples with Smooth Unique Information**

    Harutyunyan et al. ICLR 2021

    [arxiv](https://arxiv.org/abs/2101.06640)

- **A Tale Of Two Long Tails**

    D'souza et al. ICML 2021

    [arxiv](https://arxiv.org/abs/2107.13098)

- **HyDRA: Hypergradient Data Relevance Analysis for Interpreting Deep Neural Networks**

    Chen et al. AAAI 2021

    [arxiv](https://arxiv.org/abs/2102.02515)


