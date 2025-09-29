---
title: "Handling New Users and Items: A Comparative Study of Inductive Recommenders"
collection: publications
permalink: /publication/2025-08-29-journal-Handling-New-Users-and-Items-A-Comparative-Study-of-Inductive-Recommenders
excerpt: 'We propose a framework to evaluate inductive recommender systems on temporal splits across three real-world 
datasets. Our re-evaluation shows that aggregation-based methods consistently outperform non-aggregating ones, though 
performance varies greatly across settings.'
date: 2025-08-19
venue: 'Data Mining and Knowledge Discovery'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://doi.org/10.1007/s10618-025-01134-2'
citation: '<b>T.E. Jendal</b>,  M. Lissandrini, P. Dolog, K. Hose, 
"Handling new users and items: a comparative study of inductive recommenders," in Data Min. Knowl. Disc., 2025'
---

Usually, recommender systems are trained on a set of users and items and then used to recommend new user-item pairings
among those seen during training. As users and items are added continuously, there is a pressing need to provide 
recommendations for new users and items, i.e., for users and items not seen during training. Solutions to this problem 
exploit techniques like meta-learning or auxiliary information encoded in knowledge graphs to learn an “inductive bias”.
Yet, most existing works can either recommend for new users or new items not seen during training but not both. Further,
existing methods have rarely been compared to each other. Finally, existing evaluations of these methods use a random 
split of training data, and thus do not consider temporal splits of ratings in training and testing. This setting 
ensures testing is correctly performed on user interactions that actually occur after the training period. In this 
paper, we propose a framework for training and testing the methods on three real world datasets, and perform a deeper 
analysis of each dataset to better understand the effect of emerging popularity trends. As a result, our re-evaluation
of state-of-the-art methods identifies strong architectures and solutions for inductive recommendation. We find that 
inductive methods that perform aggregation are able to outperform non-aggregating methods in all settings; performances
vary greatly across settings, pointing to new important research questions.