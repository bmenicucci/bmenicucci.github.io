---
layout: single
title: il Team
permalink: /il-team/
header:
  overlay_filter: rgba(235,235,235, 0.5)
  overlay_image: teamwork.jpg
sidebar: 
  nav: chisiamo
category: About us
tag: M&A
carousel:
  - image: /images/post01.jpg
  - image: /images/post02.jpg
  - image: /images/post03.jpg
---

	  
![](/images/work-in-progress.png)

{% if page.carousel %}
  <div class="flexslider">
    <ul class="slides">
      {% for slides in page.carousel %}
      <li>
        <img src="{{ slides.image }}">
      </li>
      {% endfor %}
    </ul>
  </div>
{% endif %}

<!-- Place somewhere in the <body> of your page
<div class="flexslider">
  <ul class="slides">
    <li>
      <img src="/images/post01.jpg" />
    </li>
    <li>
      <img src="/images/post02.jpg" />
    </li>
    <li>
      <img src="/images/post03.jpg" />
    </li>
  </ul>
</div> -->