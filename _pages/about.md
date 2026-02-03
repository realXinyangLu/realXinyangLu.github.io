---
permalink: /
title: "👋 Hi! I'm Xinyang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in the [School of Computing](https://www.comp.nus.edu.sg/) at National University of Singapore ([NUS](https://www.nus.edu.sg/)), advised by Prof. [Bryan Low](https://www.comp.nus.edu.sg/~lowkh/) and Prof. [See-Kiong Ng](https://www.comp.nus.edu.sg/~ngsk/). My current research is on **Machine Unlearning** and **Data Attribution** in **Large Language Models**.

I obtained my B.Sc. in Electrical and Electronic Engineering at Nanyang Technological University ([NTU](https://www.ntu.edu.sg/)) in 2018.

You can find my CV here: [Xinyang Lu CV](../assets/Xinyang%20Lu%20CV.pdf)



<h2>Publications</h2>

{% assign current_year = "" %}

{% for post in site.publications reversed %}
  {% capture post_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  
  {% if post_year != current_year %}
    {% assign current_year = post_year %}
    <h3 style="border-bottom: 1px solid #eee; padding-bottom: 5px; margin-top: 30px;">{{ current_year }}</h3>
  {% endif %}

  {% include pub-row.html %}
{% endfor %}