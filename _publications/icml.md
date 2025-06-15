---
title: "Active feature acquisition via explainability-driven ranking"
collection: publications
category: conferences
permalink: /publication/icml
excerpt: ''
date: 2025-07-12
venue: 'International conference on machine learning (ICML)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
In many practical applications, including medicine, acquiring all relevant data for machine learning models is often infeasible due to constraints on time, cost, and resources. This makes it important to selectively acquire only the most informative features, yet traditional static feature selection methods fall short in scenarios where feature importance varies across instances. Here, we propose an active feature acquisition (AFA) framework, which dynamically selects features based on their importance to each individual case. Our method leverages local explanation techniques to generate instance-specific feature importance rankings. We then reframe the AFA problem as a feature prediction task, introducing a policy network grounded in a decision transformer architecture. This policy network is trained to select the next most informative feature by learning from the feature importance rankings. As a result, features are acquired sequentially, ordered by their predictive significance, leading to more efficient feature selection and acquisition. Extensive experiments on multiple datasets demonstrate that our approach outperforms current state-of-the-art AFA methods in both predictive accuracy and feature acquisition efficiency. These findings highlight the promise of an explainability-driven AFA strategy in scenarios where the cost of feature acquisition is a key concern.