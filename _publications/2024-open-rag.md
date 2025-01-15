---
title: "Open-RAG: Enhanced Retrieval-Augmented Reasoning with Open-Source Large Language Models"
collection: publications
category: conferences
permalink: /publication/2024-open-rag
excerpt: 'Proposes a new RAG system for Multi hop Question Answering'
date: 02-10-2024
venue: 'EMNLP Findings'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2410.01782'
citation: 'Islam, S. B., Rahman, M. A., Hossain, K. S. M., Hoque, E., Joty, S., & Parvez, M. R. (2024). OPEN-RAG: Enhanced Retrieval-Augmented Reasoning with Open-Source Large Language Models. arXiv preprint arXiv:2410.01782.'
---

Retrieval-Augmented Generation (RAG) has been shown to enhance the factual accuracy of Large Language Models (LLMs), but existing methods often suffer from limited reasoning capabilities in effectively using the retrieved evidence, particularly when using open-source LLMs. To mitigate this gap, we introduce a novel framework, Open-RAG, designed to enhance reasoning capabilities in RAG with open-source LLMs. Our framework transforms an arbitrary dense LLM into a parameter-efficient sparse mixture of experts (MoE) model capable of handling complex reasoning tasks, including both single- and multi-hop queries. Open-RAG uniquely trains the model to navigate challenging distractors that appear relevant but are misleading. As a result, Open-RAG leverages latent learning, dynamically selecting relevant experts and integrating external knowledge effectively for more accurate and contextually relevant responses. In addition, we propose a hybrid adaptive retrieval method to determine retrieval necessity and balance the trade-off between performance gain and inference speed. Experimental results show that the Llama2-7B-based Open-RAG outperforms state-of-the-art LLMs and RAG models such as ChatGPT, Self-RAG, and Command R+ in various knowledge-intensive tasks. We open-source our code and models at this https URL
