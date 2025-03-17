---
title: "TaCo: Enhancing Cross-Lingual Transfer for Low-Resource Languages in LLMs through Translation-Assisted Chain-of-Thought Processes"
collection: publications
category: manuscripts
permalink: /publication/22024-05-12-taco-number-1
excerpt: 'This paper introduces TaCo, a novel approach to improve cross-lingual transfer for low-resource languages in Large Language Models.'
date: 2024-05-12
venue: 'ICLR 2024 Workshop PML4LRS'
paperurl: 'https://openreview.net/forum?id=02MLWBj8HP'
# citation: 'Upadhayay, B., & Behzadan, V. (2024). &quot;TaCo: Enhancing Cross-Lingual Transfer for Low-Resource Languages in LLMs through Translation-Assisted Chain-of-Thought Processes.&quot; <i>5th Workshop on practical ML for limited/low resource settings</i>.'
---

Creating multilingual LLMs poses a significant challenge. Pretraining or fine-tuning LLMs to adopt new languages is evidently very costly. Furthermore, there exist limitations concerning benchmark datasets and the metrics used to measure model performance in multilingual settings. This paper proposes cost-effective solutions to both aforementioned challenges. Firstly, we introduce the Multilingual Instruction-Tuning Dataset (MITS), comprised of Alpaca-52K, Dolly-15K, and Vicuna Benchmark translations into 132 languages. Secondly, we propose a new method called TaCo: Translation-Assisted Cross-Linguality, which utilizes translations in a chain-of-thought process to instruction-tune LLMs on new languages through a curriculum-learning process. As a proof of concept, we experimented with the instruction-tuned Guanaco-33B model, performing further instruction tuning using our proposed TaCo method in three low-resource languages and one high-resource language. Our results indicate that the TaCo method impresses GPT-4 with an 82% score for a low-resource language in the Vicuna Benchmark dataset, doubling the performance in contrast to instruction tuning alone. Furthermore, TaCo shows promise in creating multilingual LLMs, even for low-resource languages. We have released our datasets and model adapters, encouraging the research community to utilize these resources to advance work on multilingual LLMs.