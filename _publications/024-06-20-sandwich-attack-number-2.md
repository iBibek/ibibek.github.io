---
title: "Sandwich Attack: Multi-language Mixture Adaptive Attack on LLMs"
collection: publications
category: manuscripts
permalink: /publication/sandwich-attack-on-llms
excerpt: 'This paper introduces the Sandwich attack, a novel multi-language mixture attack that can manipulate state-of-the-art LLMs into generating harmful and misaligned responses.'
date: 2024-06-20
venue: 'Proceedings of the 4th Workshop on Trustworthy Natural Language Processing (TrustNLP 2024)'
paperurl: 'https://aclanthology.org/2024.trustnlp-1.16/'
# citation: 'Upadhayay, B., & Behzadan, V. (2024). &quot;Sandwich Attack: Multi-language Mixture Adaptive Attack on LLMs.&quot; <i>Proceedings of the 4th Workshop on Trustworthy Natural Language Processing (TrustNLP 2024)</i>, 208-226.'
---

Large Language Models (LLMs) are increasingly being developed and applied, but their widespread use faces challenges. These include aligning LLMs' responses with human values to prevent harmful outputs, which is addressed through safety training methods. Even so, bad actors and malicious users have succeeded in attempts to manipulate the LLMs to generate misaligned responses for harmful questions such as methods to create a bomb in school labs, recipes for harmful drugs, and ways to evade privacy rights. 

Another challenge is the multilingual capabilities of LLMs, which enable the model to understand and respond in multiple languages. Consequently, attackers exploit the unbalanced pre-training datasets of LLMs in different languages and the comparatively lower model performance in low-resource languages than high-resource ones. As a result, attackers use a low-resource languages to intentionally manipulate the model to create harmful responses. 

Many of the similar attack vectors have been patched by model providers, making the LLMs more robust against language-based manipulation. In this paper, we introduce a new black-box attack vector called the *Sandwich attack*: a multi-language mixture attack, which manipulates state-of-the-art LLMs into generating harmful and misaligned responses. Our experiments with five different models, namely Google's Bard, Gemini Pro, LLaMA-2-70-B-Chat, GPT-3.5-Turbo, GPT-4, and Claude-3-OPUS, show that this attack vector can be used by adversaries to generate harmful responses and elicit misaligned responses from these models.