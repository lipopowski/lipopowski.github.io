---
layout: default
title: ""
permalink: /
body_class: home
---

<div class="home-grid">
<div class="home-main" markdown="1">
<img class="headshot" src="{{ '/images/headshot2023.jpg' | relative_url }}" alt="Lindsay Popowski">
**Hi, I'm Lindsay!** I am a fifth year PhD candidate in computer science in the [HCI Group](https://hci.stanford.edu/) at Stanford University, advised by [Michael Bernstein](https://hci.stanford.edu/msb/). Previously, I earned a B.S. in Computer Science and Mathematics and concentrated in literature at Harvey Mudd College. I am currently supported by the [Google PhD Fellowship](https://research.google/programs-and-events/phd-fellowship/recipients/) and the [Stanford Interdisciplinary Graduate Fellowship](https://vpge.stanford.edu/fellowships-funding/vpge-fellowships/sigf-stanford-interdisciplinary-graduate-fellowship).

My research areas fall broadly within human-computer interaction (HCI) and social computing. I combine empirical work and system design/building to critique and reimagine the online spaces that mediate our social interactions. 

In general, I care about understanding how to create online spaces with better social and psychological outcomes. Currently, I'm thinking about how to improve the design of personalized social media feeds.

I am a founding member of the [Positech](https://positech.github.io) collective, a cross-institutional group of researchers who together advance a research agenda of social technology for human flourishing.

Before starting my PhD, I worked on projects related to HCI+AI for user interface applications, agent planning and scheduling, and interdisciplinary computer science education. My research focus has since changed, so I am perhaps not the best resource for current-day discussions on those topics.

</div>

<aside class="home-news">
<h2>News</h2>
<ul class="news-list">
{% for item in site.data.news %}
<li><span class="news-date">{{ item.date }}</span>{{ item.text | markdownify }}</li>
{% endfor %}
</ul>
</aside>
</div>