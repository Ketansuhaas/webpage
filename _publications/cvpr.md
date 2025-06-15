---
title: "Progressive Prompt Detailing for Improved Alignment in Text-to-Image Generative Models"
collection: publications
category: books
permalink: /publication/cvpr
excerpt: 'Selected for oral presentation at AI4CC and poster presentation at GMCV'
date: 2025-07-12
venue: 'Computer vision and pattern recognition (CVPR)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Text-to-image generative models often struggle with long prompts detailing complex scenes, diverse objects with distinct visual characteristics and spatial relationships. In this work, we propose SCoPE (Scheduled interpolation of Coarse-to-fine Prompt Embeddings), a training-free method to improve text-to-image alignment by progressively refining the input prompt in a coarse-to-fine-grained manner. Given a detailed input prompt, we first decompose it into multiple sub-prompts which evolve from describing broad scene layout to highly intricate details. During inference, we interpolate between these sub-prompts and thus progressively introduce finer-grained details into the generated image. Our training-free plug-and-play approach significantly enhances prompt alignment, achieves an average improvement of up to +4% in Visual Question Answering (VQA) scores over the Stable Diffusion baselines on 85% of the prompts from the GenAI-Bench dataset.
