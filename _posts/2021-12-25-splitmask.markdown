---
layout: post
title:  "Are Large-scale Datasets Necessary for Self-Supervised Pre-training?"
image: images/splitmask.png
categories: research
authors: "<strong>Alaaeldin El-Nouby</strong>, Gautier Izacard, Hugo Touvron, Ivan Laptev, Hervé Jegou, Edouard Grave"
venue: "Under Review"
arxiv: https://arxiv.org/abs/2112.10740
---
Pre-training models on large scale datasets, like ImageNet, is a standard practice in computer vision. We consider a self-supervised pre-training scenario that only leverages the target task data. We consider datasets, like Stanford Cars, Sketch or COCO, which are order(s) of magnitude smaller than Imagenet. Our study shows that denoising autoencoders, such as BEiT or a variant that we introduce in this paper, are more robust to the type and size of the pre-training data than popular self-supervised methods trained by comparing image embeddings.
