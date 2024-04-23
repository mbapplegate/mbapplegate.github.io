---
title: Self-supervised denoising of volumetric biomedical images
excerpt: "Improving medical images with machine learning is hard because of the difficulty in collecting datasets that contain gold standard, or ground truth images. Self-supervised methods can learn to denoise images solely from noisy data. In this work, I show how similarities between adjacent images in a volume can be used to remove noise from a variety of volumetric biomedical image data."
date: 2023-03-27
image: /images/denoiseWebsiteFigure.png
publink: https://pubmed.ncbi.nlm.nih.gov/36992871/
collection: research
---

Traditional machine learning techniques are supervised, meaning they require examples of both the input data and the completed task to learn from. For denoising medical imaging, it is difficult (or impossible) to collect this type of data. Whether it's a limitation of the imaging technology, or respect for patient and physician time, noise-free images are almost never available. Recently, self-supervised denoising algorithms have been developed that can remove noise without access to examples of the clean data. However, these algorithms often require special acquisition protocols that can be difficult and time-consuming, or impossible for some imaging geometries. In this work I show how if volumetric data are available and sampled at a high enough frequency, similarities between adjacent slices can be exploited to denoise images. Many volumetric images are collected at the Nyquist rate to preserve maximum information in the images, which means that adjacent images arise, in part, from the same physical structures. This guarantees that the images are largely similar and can be used for denoising with minimal errors.
