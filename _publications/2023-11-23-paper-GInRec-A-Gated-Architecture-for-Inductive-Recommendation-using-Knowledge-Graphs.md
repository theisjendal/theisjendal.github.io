---
title: "GInRec: A Gated Architecture for Inductive Recommendation using Knowledge Graphs"
collection: publications
permalink: /publication/2023-11-23-GInRec-A-Gated-Architecture-for-Inductive-Recommendation-using-Knowledge-Graphs
excerpt: 'We propose GInRec, a state-of-the-art method using a graph neural network with relation-specific gates and a 
knowledge graph, to provide better recommendations for new users and items, outperforming existing inductive methods. 
Our work reevaluates state-of-the-art methods, identifies improved evaluation protocols, and highlights flaws 
in previous conclusions.'
date: 2023-11-23
venue: 'Proceedings of the Fifth Knowledge-aware and Conversational Recommender Systems Workshop (KaRS)'
paperurl: 'https://ceur-ws.org/Vol-3560/long6.pdf'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'T. E. Jendal, M. Lissandrini, P. Dolog, and K. Hose, “GInRec: A gated architecture for inductive recommendation using knowledge graphs,” in KaRS, 2023.'
---

We have witnessed increasing interest in exploiting KGs to integrate contextual knowledge in recommender systems in
addition to user-item interactions, e.g., ratings. Yet, most methods are transductive, i.e., they represent instances seen
during training as low-dimensionality vectors but cannot do so for unseen instances. Hence, they require heavy retraining
every time new items or users are added. Conversely, inductive methods promise to solve these issues. KGs enhance
inductive recommendation by offering information on item-entity relationships, whereas existing inductive methods rely
purely on interactions, which makes recommendations for users with few interactions sub-optimal and even impossible
for new items. In this work, we investigate the actual ability of inductive methods exploiting both the structure and
the data represented by KGs. Hence, we propose GInRec, a state-of-the-art method that uses a graph neural network
with relation-specific gates and a KG to provide better recommendations for new users and items than related inductive
methods. As a result, we re-evaluate state-of-the-art methods, identify better evaluation protocols, highlight unwarranted
conclusions from previous proposals, and showcase a novel, stronger architecture for this task. The source code is available
at: [https://github.com/theisjendal/kars2023-recommendation-framework](https://github.com/theisjendal/kars2023-recommendation-framework).
