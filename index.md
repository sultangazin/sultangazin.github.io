---
layout: splash
author_profile: false
permalink: /
toc: flase
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
  caption: "Photo credit: "
excerpt: "La la la"
feature_row:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/bio-photo.jpg
    alt: "Bio photo"
    title: "Alimzhan Sultangazin"
    excerpt: {{ author.bio | markdownify }}
---

{% include author-profile.html type="left" %}

{% include feature_row id="feature_row2" %}

# About

Soon-to-graduate PhD candidate in Electrical and Computer 
Engineering from UCLA with more than 5 years of experience 
in **non-linear 
control and estimation** algorithms seeking a research or 
software engineer position. Independent problem solver with 
experience leading research and development – from 
conception to implementation – of cutting-edge algorithms 
for **privacy in optimal control** and **learning from 
demonstrations**. Fast learner with a deep understanding of 
**nonlinear optimization**, **motion planning algorithms**, 
**probabilistic robotics**, **deep learning**, **computer vision**, 
and **reinforcement learning**. Has a vast experience of 
clearly **communicating technical ideas** and a demonstrable 
**track record of publications** in major journals and 
conferences. Adept in the modern software engineering tools
and practices.
{: .text-justify}

# Experience

{% include feature_row %}