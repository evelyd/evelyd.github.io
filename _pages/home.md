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

I have been at the Italian Institute of Technology since 2022 when I started a position as a research fellow in the Artificial and Mechanical Intelligence (AMI). Since 2023 I have been working toward my PhD in physics-informed learning for legged robot policies. Since 2026 I have been continuing this research with the Sustainable Artificial Intelligence Lab (SAIL). Before that, I completed my M.S. in Systems and Control in 2021 at Delft University of Technology in the Netherlands. My master thesis, "Automatic Controller Selection on a Humanoid Robot using Optimization Techniques", was done at the LARSEN lab at INRIA Nancy - Grand Est, France. I earned my B.S. degree in Mechanical Engineering in 2019 from Northeastern University in Boston.
