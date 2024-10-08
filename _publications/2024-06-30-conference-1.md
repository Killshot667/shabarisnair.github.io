---
title: "Improving Rare-Word Recognition Of Whisper In Zero-Shot Settings"
collection: publications
category: conferences
permalink: /publication/2024-06-30-conference-1
excerpt: ''
date: 2024-12-03
venue: "Spoken Language Technology'24"
status: "Published"
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://killshot667.github.io/shabarisnair.github.io/files/SLT_2024.pdf'
citation: 'Yash Jogi*, Vaibhav Aggarwal*, Shabari S Nair, Yash Verma, Aayush Kubba'
---

Whisper, despite being trained on 680K hours of web-scaled audio data, faces difficulty in recognizing rare words like domain-specific terms, with a solution being contextual bias- ing through prompting. To improve upon this method, in this
paper, we propose a supervised learning strategy to fine-tune Whisper for contextual biasing instruction. We demonstrate that by using only 670 hours of Common Voice English set for fine-tuning, our model generalizes to 11 diverse open- source English datasets, achieving a 45.6% improvement in recognition of rare words and 60.8% improvement in recognition of words unseen during fine-tuning over the baseline method. Surprisingly, our model’s contextual biasing ability generalizes even to languages unseen during fine-tuning.