---
title: "MolReFlect: Towards In-Context Fine-grained Alignments between Molecules and Texts"
collection: publications
permalink: /publication/2024-molreflect
excerpt: 'Molecule Discovery, Large Language Models'
date: 2024-11-22
venue: 'arXiv preprint'
paperurl: https://arxiv.org/pdf/2411.14721
citation: 'Jiatong Li, Yunqing Liu, Wei Liu, Jingdi Le, Di Zhang, Wenqi Fan, Dongzhan Zhou, Yuqiang Li, and Qing Li. (2024). MolReFlect: Towards In-Context Fine-grained Alignments between Molecules and Texts. arXiv preprint arXiv:2411.14721'
---

Molecule discovery is a pivotal research field, impacting everything from the medicines we take to the materials we use. Recently, Large Language Models (LLMs) have been widely adopted in molecule understanding and generation, yet the alignments between molecules and their corresponding captions remain a significant challenge. Previous endeavours often treat the molecule as a general SMILES string or molecular graph, neglecting the fine-grained alignments between the molecular sub-structures and the descriptive textual phrases, which are crucial for accurate and explainable predictions. In this case, we introduce MolReFlect, a novel teacher-student framework designed to contextually perform the molecule-caption alignments in a fine-grained way. Our approach initially leverages a larger teacher LLM to label the detailed alignments by directly extracting critical phrases from molecule captions or SMILES strings and implying them to corresponding sub-structures or characteristics. To refine these alignments, we propose In-Context Selective Reflection, which retrieves previous extraction results as context examples for teacher LLM to reflect and lets a smaller student LLM select from in-context reflection and previous extraction results. Finally, we enhance the learning process of the student LLM through Chain-of-Thought In-Context Molecule Tuning, integrating the fine-grained alignments and the reasoning processes within the Chain-of-Thought format. Our experimental results demonstrate that MolReFlect enables LLMs like Mistral-7B to significantly outperform the previous baselines, achieving SOTA performance on the ChEBI-20 dataset. This advancement not only enhances the generative capabilities of LLMs in the molecule-caption translation task, but also contributes to a more explainable framework.

<!-- Our codes will be available here:
[codes are available here](https://github.com/phenixace/ICMA)

You could first download our model weighst via [Huggingface Link](https://huggingface.co/phenixace/) -->

[Download paper here](https://arxiv.org/pdf/2411.14721)
