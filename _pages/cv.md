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
* Bachelors & Masters: Indian Institute of Technology, Kharagpur
* Courses in Mandarin: National Taiwan Normal University, National Taiwan University
  * Recipient of Huayu Enrichment Scholarship
* Languages: Fluent in Hindi, English and Mandarin (traditional characters)
  
Notable Projects
=====
* [GLIACloud] Highlight detection in soccer videos
  * Built a simple CNN + RNN model which was trained on labeled soccer videos from Chinese Super League
* [PicCollage] Distillation of CLIP model
  * Distilled the ViT component of the CLIP model (24MB only), which was then deployed on edge and is currently in use by multiple apps
  * Some details are available [here](https://tech.pic-collage.com/distillation-of-clip-model-and-other-experiments-f8394b7321ce), but we did more work later which is not covered by the article
  * Extracted attention values from the transformer layer to act as a proxy for saliency patches
* [PicCollage] Training a GNN for photo to sticker recommendation
  * Implemented a variant of [CompGCN](https://github.com/malllabiisc/CompGCN)
  * The most important change was that our model was inductive while the original implementation was transductive. This was done by a) fixing the initial node embedding to be a CLIP embedding and b) learning a transformation to map the initial node embedding instead of changing the node values directly
* [PicCollage] Transition detection in videos
  * This was done by looking at the spectral properties of the cosine similarity matrix of the video frames (Spectral Graph Theory to the rescue!)
* [PicCollage] Image quality assessment using multi-modal projection matrices
  * Turned out to be more effective than a model trained on NIMA
* [PicCollage] Bringing Generative AI related technologies to build products/features on
  * Set up training pipelines for dreambooth, LoRA and ControlNet

Skills
======
* Setting a ML team from the ground up
* Programming: Python, Julia, React
* Machine Learning
  * Statistical models, pre-deep-learning era tools, information theory
  * Deep Learning: hands-on with transformers, GNNs, self-supervised learning among other areas
  * Generative AI: the good old VAE, normalizing flows, diffusion models and LLMs
  * Multi-modality: I was using [canonical correlation analysis](https://en.wikipedia.org/wiki/Canonical_correlation) in the pre-CLIP era to compare image and text embeddings. Things changed after CLIP and cross-attention modules. Intimately familiar with CLIP models and its derivatives. 
  * If all else fails, `SVD is all you need`.
* Math
  * Created [Linear Algebra for Programmers](https://www.linearalgebraforprogrammers.com/)
  * (Old work, discontinued) [Visual essays on math-related topics](https://tinyvolt.com/)
* Problem solving with math, programming and a wee bit of engineering
* A growing awareness of important problems to solve/critical questions to ask for which I don't have good solutions/answers
