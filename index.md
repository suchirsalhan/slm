---
layout: default
title: Small and Cognitively-Inspired Language Models
---

Modern Natural Language Processing (NLP) is dominated by large pre-trained, highly parameterised neural networks trained on extremely large web-mined corpora. Training and inference using such models are incredibly costly, and the benefits of the pre-train/fine-tune paradigm are unclear for domain-specific downstream tasks. Recent advances in language modeling consist in pretraining highly parameterized neural networks on extremely large web-mined text corpora. Training and inference with such models can be costly in practice, which incentivizes the use of smaller counterparts. Additionally, theoretical linguists and cognitive scientists have highlighted several weaknesses with state-of-the-art foundation models. 

  <p>
<b> Architecture & Computational Complexity:</b> The viability of 'Small LMs' as a coherent research programme relies on a successful consideration of efficiency, acceleration and architectural questions. There is a growing recognition that the computational complexity of self-attention in Transformers is suboptimal in various respects. 
<br>
<br>

<b> Cognitively-inspired AI:</b> The emergent capabilities of Transformers are subject to a great deal of interpretability work, however there is a clear mismatch between human language acquisition (which is data-efficient in many regards) and the data-hungriness of Transformers. I am personally very invested in research questions that draw on insights from language acquisition to guide architectural alternatives to 'vanilla' Transformers. 

<br>
<br>

<b> Training Dynamics, Evaluation and Scalability:</b> Benchmarking is a fundamental part of guiding contemporary AI systems, and requires an inherently interdisciplinary approach to be meaningful.  Leading metrics are often variously incomplete or inadequate. However, equally, we should not only be interested reporting overall scores and metrics – training dynamics of models are equally important.

<br>
<br>

<b> Domain-Specificity:</b> Practioners interested in domain-specific Machine Learning (e.g., in educational, legal, biomedical domains) do not have sufficient control over the capabilities of Language Models. While novel post-training techniques are addressing this in various ways, techniques and strategies related to pretraining are equally important. The ethical and societal importance of domain-specific Language Models are huge. It is vitally important that research into the control over systems are not relegated solely to industry and Big Tech – who are guide by a different set of commercial priorities– particularly for research areas associated with large human costs (in labour and social terms). 
  </p>




---

## Table of contents
{% for item in site.posts %}
* [{{ item.title }}]({{ site.baseurl }}{{ item.url }}){% if item.author %} by {{ item.author }}{% endif %}{% endfor %}
