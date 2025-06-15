---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Artificial Intelligence, Boston University, 2025  
  * GPA: 3.96/4.00  
  * Thesis Track (Advisor: Dr. Vijaya B. Kolachalama) 
* B.Tech. in Electrical Engineering, Indian Institute of Technology Roorkee, 2023  
  * CGPA: 8.65/10.00

Research experience
======
* June 2025 – Present: Research Staff, Kolachalama Lab, Boston University  
  * Developed clinical LLM systems for interactive diagnoses and multimodal data processing.  

* Sept 2023 – May 2025: Graduate Researcher, Kolachalama Lab, Boston University  
  * Designed novel AFA methods using reinforcement learning and CMI-based rewards (2–10% performance gain).  
  * Created a zero-shot classification strategy for EEG signals.  
  * Led data curation and LLM post-training for multimodal medical AI.

* Sept 2024 – May 2025: Research Collaborator, Deepti Research Group, Boston University  
  * Proposed SCoPE: scheduling coarse-to-fine prompt embeddings in diffusion models.  
  * Demonstrated improvements over stable diffusion on 83% of prompts using CLIP-based alignment techniques.

* May 2024 – May 2025: Research Assistant, Banaji Implicit Social Cognition Lab, Harvard University  
  * Identified humanlike cognitive patterns in GPT-4o; developed batch-processing LLM pipelines.  
  * Founded the SHASM group: The Science of Human and Artificial Social Minds.

Industry experience
======
* May 2025 – Present: AI Engineer, Clairyon  
  * Built and deployed Model Context Protocol (MCP) servers for hospital systems.  
  * Created agentic AI systems for automating clinical workflows in the cloud.

* May 2024 – Aug 2024: AI Engineer Intern, NourishedRx  
  * Designed and deployed Generative AI tools (e.g., AskBetty chatbot using RAG, AWS Bedrock).  
  * Created LLM agents for querying BigQuery/FHIR and summarizing health data.  
  * Automated voice call transcription and note generation using Amazon Transcribe and Bedrock.

* May 2022 – July 2022: Software Development Engineer Intern, Slice  
  * Built backend RESTful APIs in Java Spring Boot for payment integration with Juspay.  
  * Improved transaction reliability by 15% via error-handling and retry logic.

Skills
======
* Programming: Python, C++, JavaScript, TypeScript, SQL  
* AI/ML Frameworks: PyTorch, TensorFlow, Scikit-learn, OpenCV, CUDA  
* Tools & Platforms: AWS (Bedrock, Lambda, Amplify), GCP (Vertex AI, BigQuery), Kubernetes, Docker  
* Libraries & APIs: HuggingFace, LangChain, LlamaIndex, Pinecone, TorchServe  
* Specialties: LLMs (GPT, LLaMA, Mistral), CLIP, RAG, RLHF, QLoRA, LoRA, PEFT  
* Full-Stack: ReactJS, Redux, Streamlit, Gradio  
* Others: Git, VS Code, Anaconda, Terminal, WandB

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Honors and Achievements
======
* Bronze Medalist – Optiver Trading at the Close, Kaggle Competition, 2024  
* ICPC Asia Regionals – Represented IIT Roorkee, 2021 & 2022  
* JEE Advanced 2019 (AIR 1640) – FIITJEE Award (INR 100,000)  
* JEE Main 2019 (AIR 1390)  
* KVPY Fellow (AIR 1237), 2019 – Govt. of India Scholarship  
* Indian National Physics Olympiad – State Rank 7, 2019

Projects
======
* SCoPE Diffusion  
  * Improved alignment in text-to-image models through coarse-to-fine prompt interpolation.  
* Gesture Controller  
  * Built a gesture-controlled game interface using OpenCV and PySide6, optimized for RPG/FPS/Racing genres.
