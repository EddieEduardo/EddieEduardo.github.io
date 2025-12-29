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

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
