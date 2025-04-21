---
title: "SPROUT"
permalink: /sprout/
overlay_image: /assets/images/SPROUT.png
layout: single
classes: wide
date: 
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/AITree.png
  caption: "Photo credit: Marco Camaiti"
excerpt: Welcome to the wonderful world of Phenomics with AI
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitud in. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

---

## Introducing SPROUT: Semi-automated Parcellation of Region Outputs Using Thresholding

The increased availability of 3D image data requires improving the efficiency of digital segmentation, currently relying on manual labelling, especially when separating structures into multiple components. Automated and semi-automated methods to streamline segmentation have been developed, such as deep learning and smart interpolation, but require pre-labelled data, and specialized hardware and software. Deep learning models in particular often require the manual creation of extensive training data, particularly for complex multi-class segmentations. Here, we introduce SPROUT, a novel, semi-automated computer vision method providing a time-efficient and user-friendly pipeline for segmenting and parcellating image data. SPROUT generates seeds (representing parts of an object) based on specified density thresholds and erosion of connected components, to achieve element separation. Seeds are grown to obtain fully-parcellated segmentations. We compare SPROUT’s performance to that of smart interpolation and apply it to diverse datasets to demonstrate the utility and versatility of this open-source 3D segmentation method.

<br>

> Read more about SPROUT in our Bioarxiv preprint: Introducing SPROUT (Semi-automated Parcellation of Region Outputs Using Thresholding): an adaptable computer vision tool to generate 3D segmentations. Yichen He, Marco Camaiti, Lucy E. Roberts, James M. Mulqueeney, Marius Didziokas, Anjali Goswami. bioRxiv 2024.11.22.624847 at https://doi.org/10.1101/2024.11.22.624847

<br>

<figure>
  <img
    src="https://raw.githubusercontent.com/PhAInomics/PhAInomics.github.io/main/assets/images/FLOWCHART2.jpg"
    alt="SPROUT pipeline"
  >
  <figcaption>Summary of the SPROUT pipeline</figcaption>
</figure>
