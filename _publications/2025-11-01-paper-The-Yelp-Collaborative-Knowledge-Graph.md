---
title: "The Yelp Collaborative Knowledge Graph"
collection: publications
permalink: /publication/2025-11-01-paper-The-Yelp-Collaborative-Knowledge-Graph
excerpt: 'We present the Yelp Collaborative Knowledge Graph (YCKG), a new Knowledge Graph built from the Yelp Open Dataset that properly integrates taxonomies, product categories, business locations, and the Yelp social network following state-of-the-art construction practices.'
date: 2025-11-01
venue: 'CIKM: Conference on Information and Knowledge Management'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://doi.org/10.1145/3746252.3761615'
citation: '<b>T.E. Jendal</b>, M. Corfixen, M. Olesen, P. Dolog, K Hose, D. Dell''Aglio, M. Lissandrini, 
"The Yelp Collaborative Knowledge Graph," in CIKM, 2025'
---

Yelp Open Dataset (YOD) is a widely used dataset for Recommender Systems (RS). Multiple Knowledge Graphs (KGs) have been built for YOD, but they have various issues: the conversion processes usually do not follow state-of-the-art methodologies, fail to properly link to other KGs, do not link to existing vocabularies, ignore important data, and are generally of small size. Instead, we present the Yelp Collaborative Knowledge Graph (YCKG), where we correctly integrating taxonomies, product categories, business locations, and the Yelp social network, through common practices within the semantic web community, overcoming all these issues. As a result, the YCKG includes 150k businesses and 16.9M reviews from 1.9M distinct real users, resulting in over 244 million triples, 144 distinct predicates, for about 72 million resources, with an average in-degree and out-degree of 3.3 and 12.2, respectively. Further, we release both the data and the code used to generate the KG for inspection and further extensions. This dataset can be used to develop and test both recommendation and data-mining algorithms able to exploit rich and semantically meaningful knowledge. We publicize the code for the CKG construction on: https://github.com/MadsCorfixen/The-Yelp-Collaborative-Knowledge-Graph.
