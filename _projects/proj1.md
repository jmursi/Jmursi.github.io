---
title: "VQA for the Visually Impaired"
excerpt: "[A Visual Question Answering System to help the visually impaired with navigation](https://yusufali98.github.io/Visual-Reasoning-for-the-Visually-Impaired/) <br/><img src='Screenshot 2022-10-15 at 3.37.11 PM.png' width="200">"
collection: projects
---

We built a VQA model to answer navigation-related questions asked by the visually impaired. The dataset consists of images that are clicked by people who are visually impaired, hence the dataset also consists of images that are blurred, not properly focused etc. We perform clustering to find images suitable for our use-case - navigation. To build the model, we employed pre-trained VGGNet and BERT-large models for image feature extraction and text embedding extraction respectively. And a neural network architecture on the concatenated embeddings to answer queries. 


