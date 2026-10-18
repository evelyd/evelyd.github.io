---
title: "Home"
layout: homelay
permalink: /
---

<h1 class="home-hero">{{ site.name }}</h1>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

Studying how physical priors and model-based techniques can be leveraged to improve the quality of legged robot locomotion policies. In particular, I'm interested in morphological symmetries and Koopman theory applied to reinforcement learning.

{% capture selected %}{% bibliography --query @*[selected=true] %}{% endcapture %}
{% if selected contains "pub-entry" %}
## Selected publications

<div class="section-card selected-pubs" markdown="0">
{{ selected }}
<p style="margin: var(--space-4) 0 0;"><a href="{{ '/publications' | relative_url }}">All publications &rarr;</a></p>
</div>
{% endif %}

## About me

Evelyn D'Elia received her B.S. degree in Mechanical Engineering in 2019 from Northeastern University in Boston, and her M.S. in Systems and Control in 2021 from Delft University of Technology in the Netherlands. She completed her thesis, "Automatic Controller Selection on a Humanoid Robot using Optimization Techniques", at the LARSEN lab at INRIA Nancy - Grand Est, France. She started working as a research fellow in the Artificial and Mechanical Intelligence (AMI) lab at IIT in 2022, and since 2023 has been completing her PhD on physics-informed learning for legged robot policies. She has continued her research on this topic with SAIL since January 2026.