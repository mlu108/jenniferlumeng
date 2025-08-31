---
layout: page
title: "Complex Event Representation"
img: assets/img/project_world_event.jpeg
description: "Final Project for CS333 Natural Language Processing (Professor: Carolyn Anderson): Instilling Inductive Bias in Language Models for Complex Historical Event Representation"
importance: 3
category: main
---

This project investigates whether instilling inductive biases into large language models (LLMs) can improve their ability to represent and reason about complex historical events. We argue that effective event embeddings—capturing both semantic content and relational structure—are essential for advancing model understanding. Complex events, such as The Rebellion of 1923, consist of interdependent subevents, entities, and concepts, and are situated within broader causal chains (e.g., the assassination of Archduke Franz Ferdinand leading to World War I and subsequently the Paris Peace Conference). Capturing such semantic detail and causal dependency is critical for enabling socially grounded reasoning in LLMs.

To address this challenge, we propose a hybrid architecture that integrates language and graph modalities. Semantic information is derived from dimensionality-reduced DistilBERT embeddings, while relational dependencies are modeled using Graph Neural Networks (GNNs) and Knowledge Graph Embeddings (KGE). Through ablation experiments across seven representation settings (KGE, GNN, DistilBERT, KGE+DistilBERT, GNN+DistilBERT, KGE+GNN+DistilBERT, and random+DistilBERT), we evaluate performance on binary classification using an HGB classifier and on link prediction. Results demonstrate consistent improvements, with classification robustness across random seeds and a ~26% accuracy increase in link prediction. 

This work points toward a deeper integration of computational methods with social science inquiry. By instilling inductive biases grounded in knowledge graphs, it offers a pathway to models that not only process language but also support the exploration of historical hypotheses and theories of societal change.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_world_event.jpeg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

[Project Writeup: ](/assets/pdf/project_world_event_writeup.pdf)

