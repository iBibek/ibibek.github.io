---
title: "Working Memory Attack on LLMs"
collection: publications
category: manuscripts
permalink: /publication/2025-working-memory-attack-on-llms
excerpt: 'This paper introduces a novel attack vector that exploits working memory limitations in LLMs to bypass safety mechanisms, achieving high success rates across multiple state-of-the-art models.'
date: 2025-04-17
venue: 'ICLR 2025 Workshop on Building Trust in Language Models and Applications'
paperurl: 'https://openreview.net/forum?id=II0NVPLBcI'
# citation: 'Upadhayay, B., Behzadan, V., & Karbasi, A. (2025). &quot;Working Memory Attack on LLMs.&quot; <i>ICLR 2025 Workshop on Building Trust in Language Models and Applications</i>.'
---

In-context learning (ICL) has emerged as a powerful capability of large language models (LLMs), enabling task adaptation without parameter updates. However, this capability also introduces potential vulnerabilities that could compromise model safety and security. Drawing inspiration from neuroscience, particularly the concept of working memory limitations, we investigate how these constraints can be exploited in LLMs through ICL.

We develop a novel multi-task methodology extending the neuroscience dual-task paradigm to systematically measure the impact of working memory overload. Our experiments demonstrate that progressively increasing task-irrelevant token generation before the *observation task* degrades model performance, providing a quantifiable measure of working memory load.

Building on these findings, we present a new attack vector that exploits working memory overload to bypass safety mechanisms in state-of-the-art LLMs, achieving high attack success rates across multiple models. We empirically validate this threat model and show that advanced models such as GPT-4, Claude-3.5 Sonnet, Claude-3 OPUS, Llama-3-70B-Instruct, Gemini-1.0-Pro, and Gemini-1.5-Pro can be successfully jailbroken, with attack success rates of up to 99.99%.

Additionally, we demonstrate the transferability of these attacks, showing that higher-capability LLMs can be used to craft working memory overload attacks targeting other models. By expanding our experiments to encompass a broader range of models and by highlighting vulnerabilities in LLMs' ICL, we aim to ensure the development of safer and more reliable AI systems.

