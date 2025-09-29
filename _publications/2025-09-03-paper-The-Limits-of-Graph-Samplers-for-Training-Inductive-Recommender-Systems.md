---
title: "The Limits of Graph Samplers for Training Inductive Recommender Systems"
collection: publications
permalink: /publication/2025-09-03-paper-The-Limits-of-Graph-Samplers-for-Training-Inductive-Recommender-Systems
excerpt: 'We investigate graph-based recommender systems using sampling techniques to reduce training time while 
maintaining performance. Experiments show that training with 50% of the data can cut training time by up to 86% with 
minimal loss, though further reduction harms performance.'
date: 2025-09-03
venue: 'VLDB: Very Large Data Bases'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://www.vldb.org/pvldb/vol18/p2496-jendal.pdf'
citation: '<b>T.E. Jendal</b>,  M. Lissandrini, P. Dolog, K. Hose, 
"The Limits of Graph Samplers for Training Inductive Recommender Systems," in VLDB, 2025'
---

Inductive Recommender Systems are capable of recommending for new users and with new items thus avoiding the need to 
retrain after new data reaches the system. However, these methods are still trained on all the data available, requiring
multiple days to train a single model, without counting hyperparameter tuning. In this work we focus on graph-based
recommender systems, i.e., systems that model the data as a heterogeneous network. In other applications, graph
sampling allows to study a subgraph and generalize the findings to the original graph. Thus, we investigate the
applicability of sampling techniques for this task. We test on three real world datasets, with three state-of-the-art
inductive methods, and using six different sampling methods. We find that its possible to maintain performance using
only 50% of the training data with up to 86% percent decrease in training time; however, using less training data
leads to far worse performance. Further, we find that when it comes to data for recommendations, graph sampling should
also account for the temporal dimension. Therefore, we find that if higher data reduction is needed, new graph-based
sampling techniques should be studied and new inductive methods should be designed.
