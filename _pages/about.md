---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello there, I am Vinay Sisodia. I have deep interest in areas of math & machine learning. I am currently working as Technical Director, ML at [PicCollage](https://picc.co/).

What I do
======
- Bringing AI to a tech startup: building ML technologies, systems and infrastructure from the ground up
- ML Research, esp vision and language models: I am particularly interested in multi-modality, self-supervised learning and graphs
- Building and growing a machine learning team
- Building new products

Things I have built
======
- [Linear Algebra for Programmers](https://www.linearalgebraforprogrammers.com/): An e-book of visual essays to learn linear algebra from scratch.
- [TinyVolt](https://github.com/tinyvolt/): Most of my open-source work can be found here.
- [Category Theory Meetup](https://www.meetup.com/category-theory-enthusiasts/): A (now defunct) meetup group for discussing topics related to Category Theory. At some point I was really excited about this topic but soon realized that unless I familiarized myself with some advanced topics in abstract algebra, it would sound and feel like [abstract nonsense](https://en.wikipedia.org/wiki/Abstract_nonsense). Incomplete notes on this topic can be found [here](https://github.com/vinsis/applied-category-theory-slides).

Some background
======
I got into machine learning when companies were starting to build dedicated AI/ML teams. I had the privilege of being the first ML engineer in two different organizations, which allowed me to build ML systems from the ground up. Later on I took on the responsibility of growing and leading ML teams. The past few years have been quite gratifying professionally and intellectually, and I am very proud of some of the things I built during this time. 

Education
======
* Bachelors & Masters: Indian Institute of Technology, Kharagpur
* Courses in Mandarin: National Taiwan Normal University, National Taiwan University
  * Recipient of Huayu Enrichment Scholarship

Notable Projects
=====
* [GLIACloud, 2018] Highlight detection in soccer videos
  * Built a simple CNN + RNN model which was trained on labeled soccer videos from Chinese Super League
* [PicCollage, 2021] Distillation of CLIP model
  * Distilled the ViT component of the CLIP model (24MB only), which was then deployed on edge and is currently in use by multiple apps
  * Some details are available [here](https://tech.pic-collage.com/distillation-of-clip-model-and-other-experiments-f8394b7321ce), but we did more work later which is not covered by the article
  * Extracted attention values from the transformer layer to act as a proxy for saliency patches
* [PicCollage, 2021] Transition detection in videos
  * This was done by looking at the spectral properties of the cosine similarity matrix of the video frames (Spectral Graph Theory to the rescue!)
* [PicCollage, 2022] Training a GNN for photo to sticker recommendation
  * Implemented a variant of [CompGCN](https://github.com/malllabiisc/CompGCN)
  * The most important change was that our model was inductive while the original implementation was transductive. This was done by a) fixing the initial node embedding to be a CLIP embedding and b) learning a transformation to map the initial node embedding instead of changing the node values directly
* [PicCollage, 2022] Bringing Generative AI related technologies to build products/features on
  * Set up training pipelines for dreambooth, LoRA and ControlNet
