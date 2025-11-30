---
title: "Progressive Prompt Detailing for Improved Alignment in Text-to-Image Generative Models"
collection: publications
category: books
permalink: /publication/cvpr
excerpt: 'Selected for oral presentation at AI4CC and poster presentation at GMCV'
date: 2025-07-12
venue: 'AI for Content Creation Workshop, Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://arxiv.org/abs/2503.17794'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: '<strong>Saichandran, K. S.</strong>, Thomas, X., Kaushik, P., & Ghadiyaram, D. (2025). Progressive prompt detailing for improved alignment in text-to-image generative models. <i>AI for Content Creation Workshop, Conference on Computer Vision and Pattern Recognition (CVPR)</i>. <a href="https://arxiv.org/abs/2503.17794">https://arxiv.org/abs/2503.17794</a> (oral presentation)'
---
[Workshop website mention](https://ai4cc.net)
Text-to-image generative models often struggle with long prompts detailing complex scenes, diverse objects with distinct visual characteristics and spatial relationships. In this work, we propose SCoPE (Scheduled interpolation of Coarse-to-fine Prompt Embeddings), a training-free method to improve text-to-image alignment by progressively refining the input prompt in a coarse-to-fine-grained manner. Given a detailed input prompt, we first decompose it into multiple sub-prompts which evolve from describing broad scene layout to highly intricate details. During inference, we interpolate between these sub-prompts and thus progressively introduce finer-grained details into the generated image. Our training-free plug-and-play approach significantly enhances prompt alignment, achieves an average improvement of up to +4% in Visual Question Answering (VQA) scores over the Stable Diffusion baselines on 85% of the prompts from the GenAI-Bench dataset.
