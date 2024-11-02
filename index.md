---
layout: default
title: Small and Cognitively-Inspired Language Models
---

# Overview

Modern Natural Language Processing (NLP) is dominated by large pre-trained, highly parameterised neural networks trained on extremely large web-mined corpora. Training and inference using such models are incredibly costly, and the benefits of the pre-train/fine-tune paradigm are unclear for domain-specific downstream tasks. Recent advances in language modeling consist in pretraining highly parameterized neural networks on extremely large web-mined text corpora. Training and inference with such models can be costly in practice, which incentivizes the use of smaller counterparts. Additionally, theoretical linguists and cognitive scientists have highlighted several weaknesses with state-of-the-art foundation models. 

---

## Table of contents
{% for item in site.posts %}
* [{{ item.title }}]({{ site.baseurl }}{{ item.url }}){% if item.author %} by {{ item.author }}{% endif %}{% endfor %}
