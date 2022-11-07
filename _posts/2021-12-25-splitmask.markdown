---
layout: post
title:  "Are Large-scale Datasets Necessary for Self-Supervised Pre-training?"
image: images/splitmask.png
categories: research
authors: "<strong>Alaaeldin El-Nouby</strong>, Gautier Izacard, Hugo Touvron, Ivan Laptev, Hervé Jegou, Edouard Grave"
venue: "Under Review"
arxiv: https://arxiv.org/abs/2112.10740
---
Pre-training models on large scale datasets, like ImageNet, is a standard practice in computer vision. This paradigm is especially effective for tasks with small training sets, for which high-capacity models tend to overfit. In this work, we consider a self-supervised pre-training scenario that only leverages the target task data. We consider datasets, like Stanford Cars, Sketch or COCO, which are order(s) of magnitude smaller than Imagenet. Our study shows that denoising autoencoders, such as BEiT or a variant that we introduce in this paper, are more robust to the type and size of the pre-training data than popular self-supervised methods trained by comparing image embeddings.We obtain competitive performance compared to ImageNet pre-training on a variety of classification datasets, from different domains. On COCO, when pre-training solely using COCO images, the detection and instance segmentation performance surpasses the supervised ImageNet pre-training in a comparable setting.
