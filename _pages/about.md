---
layout: about
title: Yuqi Zeng
permalink: /
sitemap: true
subtitle: B.S. student in Computer Science at Fudan University

profile:
  align: right
  image: prof_pic.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Fudan University</p>
    <p>Shanghai, China</p>
    <p><a href="mailto:yqceng23@m.fudan.edu.cn">yqceng23@m.fudan.edu.cn</a></p>

selected_papers: false # rendered below the biography to control homepage section order
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am an undergraduate student in Computer Science at Fudan University, expected to receive my B.S. in June 2027. My current GPA is 3.80/4.00.

My research interests center on large language models, agentic retrieval-augmented generation, and alignment. I am currently a Research Intern at FudanNLP Group, supervised by Prof. Xiaoqing Zheng.

{% include selected_papers.liquid %}

<h2>Selected Projects</h2>

{% assign selected_project = site.projects | where: "selected", true | first %}
<div class="row mb-4">
  <div class="col-sm-4 mb-3 mb-sm-0">
    {% if selected_project.gif %}
      <img src="{{ selected_project.gif | relative_url }}" alt="{{ selected_project.title }}" class="img-fluid rounded z-depth-1" />
    {% else %}
      <img src="{{ selected_project.img | relative_url }}" alt="{{ selected_project.title }}" class="img-fluid rounded z-depth-1" />
    {% endif %}
  </div>
  <div class="col-sm-8">
    <strong>{{ selected_project.title }}</strong>
    <p class="mt-2 mb-0">Developed at Noitom during my July 2026 internship, supporting 8 cameras, 3 people, and 3 pairs of hands at a stable 30 FPS on an RTX 4090.</p>
  </div>
</div>
