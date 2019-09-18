## RecSys 2019 Tutorial on Recommendations in a Marketplace

In recent years, two sided marketplaces have emerged as viable business models in many real world applications (e.g. Amazon, AirBnb, Spotify, YouTube), wherein the platforms have customers not only on the demand side (e.g. users), but also on the supply side (e.g. retailer, artists). Such multi-sided marketplace involves interaction between multiple stakeholders among which there are different individuals with assorted needs. While traditional recommender systems focused specifically towards increasing consumer satisfaction by providing relevant content to the consumers, two-sided marketplaces face an interesting problem of optimizing their models for supplier preferences, and visibility. In this tutorial, we consider a number of research problems which need to be address when developing a recommendation framework powering a multi-stakeholder marketplace. The tutorial provides the audience with a profound introduction to this upcoming area and presents directions of further research.


### Venue
[RecSys 2019, Copenhagen, Denmark](https://recsys.acm.org/recsys19/tutorials/#content-tab-1-4-tab)



### Introduction
Multi-sided marketplaces are steadily emerging as viable business models in many applications (e.g. Amazon, AirBnb, YouTube),
wherein the platforms have customers not only on the demand side (e.g. users), but also on the supply side (e.g. retailer). Such marketplaces involve interaction between multiple stakeholders among which there are diferent individuals with assorted needs. While traditional recommender systems focused specifcally towards increasing consumer satisfaction by providing relevant content to the consumers, multi-sided marketplaces face an interesting problem of optimizing for multiple stakeholder objectives.

In thistutorial, we consider a number ofresearch problems which need to be address when developing a recommendation framework powering a multi-stakeholder marketplace. We begin by contrasting traditional recommendations systems with those needed for marketplaces, and identify four key research areas which need to be addressed. First, we highlight the importance of a multi-objective ranking/recommendation module which jointly optimizes the different objectives of stakeholders while serving recommendations. Second, we discuss diferent ways in which stakeholders specify their objectives, and highlight key issues faced when quantifying such objectives. Third, we discuss user specifc characteristics (e.g. user receptivity) which could be leveraged while jointly optimizing business metrics with user satisfaction metrics. Furthermore, we highlight important research questions to be addressed around evaluation of such systems. Finally, we end the tutorial by discussing various diferent case studies and highlight recent fndings.



### Outline of the tutorial
```
1. Introduction
  - (Quick) Overview of traditional RecSys approaches
  - Introduction to Marketplace
  - Types & examples of marketplaces
  - Recommendation in a marketplace

  
2. Optimization Objectives in a Marketplace
  - Use-cases I - VII
    - Stakeholders & their objectives
  - Families of objectives
  - Interplay between Objectives
    - Correlation analysis
    - Supporting vs Competing objectives

  
3. Methods for Multi-Objective Ranking & Recommendations
  - Pareto optimality
  - Multi-objective models
    - Scalarization: Vectorial objectives to single objective
    - Multi-objective (constraint) optimization
    - Multi-task Learning
    - Multi-objective gradient descent
    - Multi-objective bandits
    - Multi-objective RL
  - Search & Recommendation applications

4. Matching Consumers to Suppliers
  - Bi-directional matching
  - Extracting Consumer Characteristics
  - User affinity models 

5. Multi-sided evaluation [Ben]
  - Simulation based evaluation 
  - Offline & online A/B evaluation techniques 
  - Counterfactual evaluation 
  - Trade-of analytics 

6. Conclusion
  - Open Research questions
```

### Slides
Parts 1: [link to slides (TBA)]()

Part 2: [link to slides (TBA)]()

Part 3: [link to slides (TBA)]()

Parts 4 & 5: [link to slides (TBA)]()

### Organizers
- [Rishabh Mehrotra](http://www.rishabhmehrotra.com)
Sr. Research Scientist, Spotify, London

  Rishabh Mehrotra is a Research Scientist at Spotify Research in London. He obtained his PhD in the feld of Machine Learning and Information Retrieval from University College London where he was partially supported by a Google Research Award. His current research focuses on marketplace ML and bandit based recommendations. Some of hisrecent work has been published at top conferences including WWW, SIGIR, NAACL, CIKM, RecSys and WSDM. Dr. Rishabh has co-taught a number of tutorials at leading conferences (WWW & CIKM) & has also taught courses at summer schools.

- [Benjamin Carterette](http://ir.cis.udel.edu/~carteret/)
Sr Research Manager, Spotify, NYC;
Associate Professor, University of Delaware

  Ben Carterette is a Senior Research Manager at Spotify and an Associate Professor of Computer and Information Sciences at the University of Delaware in Newark, Delaware, USA. His research focuses on evaluation in Information Retrieval, including test collection construction, evaluation measures, and statistical testing. He has published over 70 papers in venues such as ACM TOIS, SIGIR, CIKM, WSDM, ECIR, and ICTIR, winning three Best Paper Awards for his work. In addition, he has co-organized four workshops on IR evaluation and coordinated fve TREC tracks. Dr Carterette has recently been elected as the Chair for SIGIR.


