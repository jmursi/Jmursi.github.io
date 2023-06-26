---
title: "VQA for the Visually Impaired"
excerpt: "<img src='Screenshot 2023-06-27 at 1.06.24 AM.png' width='480' height='500' align='left'> 
A Visual Question Answering System to help the visually impaired with navigation. We explored large pre-trained models (VGGNet and BERT) for images and text to answer queries by the visually impaired.  [(Link to project site)](https://yusufali98.github.io/Visual-Reasoning-for-the-Visually-Impaired/) <br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
"
collection: projects
---

We built a Visual Question Answering (VQA) model to answer navigation-related questions asked by the visually impaired. The dataset consists of images that are clicked by people who are visually impaired, hence the dataset also consists of images that are blurred, not properly focused etc. We perform clustering to find images suitable for our use-case - navigation. To build the model, we employed pre-trained VGGNet and BERT-large models for image feature extraction and text embedding extraction respectively. We finally add a feed forward neural network architecture on the concatenated embeddings to answer queries for the VQA task. 


