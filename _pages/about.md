---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

About Me
======
Hi! I’m a freshly graduated PhD from Harbin Institute of Technology (Control Science & Engineering). My interests lie in computer vision and multimodal foundation models. I enjoy exploring how to bring large-scale pretraining and representation learning into real-world settings—making models not only powerful, but also efficient and practical. I also keep an eye onmodel efficiency, including lightweight architectures, more efficient training/inference, and the little engineering “gotchas” that come up during deployment.

I prefer turning ideas into systems that actually work, and then validating them in real applications. I’ve also worked on topics like image segmentation and multi-object tracking. During my PhD, my main focus was visual defect detection in industrial scenarios—making models more accurate, stable, and usable on real production lines with complex textures, changing lighting, and frequently shifting operating conditions. Along the way, I dealt with challenges around distribution shifts, limited annotations, and reliability requirements. Feel free to reach out and chat!

HI！我是刚从哈工大毕业的一枚萌新小博士（控制科学与工程）。我的兴趣主要在计算机视觉和多模态大模型方向，喜欢琢磨怎么把大规模预训练和表征学习带到真实世界里，让模型既“能打”也“跑得动”。平时也会顺带关注一些模型轻量化，更轻的结构、更高效的训练/推理，以及落地部署时会遇到的各种工程小坑。

我更喜欢把想法做成真正能用的系统，再拿到应用里去验证。也做过一些图像分割、多目标跟踪相关的研究。博士期间主要做的是工业场景的视觉缺陷检测，在纹理复杂、光照变化、工况经常变的真实产线里，把模型做得更准、更稳、更好用。过程中也接触了不少和数据分布变化、标注、可靠性要求相关的问题。欢迎来交流～

Research Interests
------
Foundation models (multi-modality foundation models), Open-set recognition, computer vision, such as detection, segmentation and multiple object tracking, and find great satisfaction in deploying models into real-world applications.

Publications
======

{% include base_path %}
{% for post in site.publications reversed limit:4 %}
  {% include archive-single-publication-card.html %}
{% endfor %}

[View all publications]({{ base_path }}/publications/)

