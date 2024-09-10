---
title: "Evaluating Open-Source Sparse Autoencoders on Disentangling Factual Knowledge in GPT-2 Small"
collection: publications
permalink: /publication/2024-11-01-paper-title-number-1
excerpt: 'A popular new method in mechanistic inter- pretability is to train high-dimensional sparse autoencoders (SAEs) on neuron activations and use SAE features as the atomic units of analy- sis. However, the body of evidence on whether SAE feature spaces are useful for causal analy- sis is underdeveloped. In this work, we use the RAVEL benchmark to evaluate whether SAEs trained on hidden representations of GPT- 2 small have sets of features that separately mediate knowledge of which country a city is in and which continent it is in. We evaluate four open-source SAEs for GPT-2 small against each other, with neurons serving as a baseline, and linear features learned via distributed align- ment search (DAS) serving as a skyline. For each, we learn a binary mask to select features that will be patched to change the country of a city without changing the continent, or vice versa. Our results show that SAEs struggle to reach the neuron baseline, and none come close to the DAS skyline. We release code here: github.com/MaheepChaudhary/SAE-Ravel'
date: 2024/9/05
venue: 'Arxiv as Pre-Print'
paperurl: 'https://arxiv.org/pdf/2409.04478'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<!-- This paper is about the number 1. The number 2 is left for future work. -->

[Download paper here](https://arxiv.org/pdf/2409.04478)

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->
