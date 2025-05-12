---
title: "SPROUT"
permalink: /sprout/
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/AITree.png
  caption: "Photo credit: Marco Camaiti"
excerpt: Welcome to the wonderful world of Phenomics with AI
---

## Introducing SPROUT: Semi-automated Parcellation of Region Outputs Using Thresholding

The increased availability of three-dimensional (3D) image data requires improving the efficiency of digital segmentation, which currently heavily relies on manual labelling, especially when separating structures into multiple components. Automated and semi-automated methods to streamline segmentation have been developed, such as deep learning and smart interpolation, but require pre-labelled data, and specialized hardware and software. Deep learning models in particular often require the manual creation of extensive training data, particularly for complex multi-class segmentations. Here, we introduce SPROUT, a novel, semi-automated computer vision method providing a time-efficient and user-friendly pipeline for segmenting and parcellating image data. SPROUT generates seeds (representing parts of an object) based on specified density thresholds and erosion of connected components, to achieve element separation. Seeds are grown to obtain fully-parcellated segmentations. We compare SPROUT’s performance to that of smart interpolation and apply it to diverse datasets to demonstrate the utility and versatility of this open-source 3D segmentation method.
<br>
> Read more about SPROUT in our [Bioarxiv preprint](https://doi.org/10.1101/2024.11.22.624847): Introducing SPROUT (Semi-automated Parcellation of Region Outputs Using Thresholding): an adaptable computer vision tool to generate 3D segmentations. Yichen He, Marco Camaiti, Lucy E. Roberts, James M. Mulqueeney, Marius Didziokas, Anjali Goswami. bioRxiv 2024.11.22.624847
<br>

<figure>
  <a href="https://github.com/EchanHe/SPROUT" target="_blank" rel="noopener">
    <img
      src="https://raw.githubusercontent.com/PhAInomics/PhAInomics.github.io/main/assets/images/FLOWCHART2.jpg"
      alt="SPROUT pipeline"
      style="width: 100%; height: auto;"
    >
  </a>
  <figcaption>Summary of the SPROUT pipeline</figcaption>
</figure>

---

**Citation:**  
Y. He, J.M. Mulqueeney, E.C. Watt, A. Salili-James, N.S. Barber, M. Camaiti,  
E.S.E. Hunt, O. Kippax-Chui, A. Knapp, A. Lanzetti, G. Rangel-de Lázaro,  
J.K. McMinn, J. Minus, A.V. Mohan, L.E. Roberts, D. Adhami,  
E. Grisan, Q. Gu, V. Herridge, S. Poon, T. West, and A. Goswami. (2024).  
Opportunities and challenges in applying AI to evolutionary morphology.  
Published in _Integrative Organismal Biology_, **obae036**.  
[Read the article here](https://academic.oup.com/iob/article/6/1/obae036/7769702)
