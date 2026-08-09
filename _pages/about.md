---
permalink: /
title: "M&M Cruz Foundation"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Building Bright Futures for Every Child

Our vision is to create lasting change by surrounding underprivileged youth with the _health_, 
_educational_, and _social support_ necessary to transform their lives and uplift their communities.
<div class="section-link-grid">
  <a class="section-link btn" href="#join-us-in-making-a-difference">
    <h3> Support our mission </h3>
    <p><em> Collaborate or sign up as a member/volunteer! </em></p>
  </a>
  <a class="section-link btn" href="/about-us/">
    <h3> Learn more about the foundation </h3>
    <p><em> Our motivation and core guiding principles. A brief glimpse of our ongoing and planned projects! </em></p>
  </a>
</div>

## How we make a difference

Everyone deserves a _safe_ place to grow and a chance at a brighter future. Here are four key pillars
to our actions:

<div class="section-link-grid">
  {% for item in site.data.mission-pillars %}
  <a href="{{ item.url | relative_url }}" class="section-link btn">
    <h3>{{ item.title }}</h3>
    <p><em>{{ item.description }}</em></p>
  </a>
  {% endfor %}
</div>

## Ongoing projects

TBD

## Join us in making a difference

Your support for our organization would be greatly appreciated in any shape for form.

<div class="section-link-grid">
  {% for item in site.data.support-links %}
  <a href="{{ item.url | relative_url }}" class="section-link btn">
    <h3 class="grid-link-head">{{ item.title }}</h3>
    <p><em>{{ item.description }}</em></p>
  </a>
  {% endfor %}
</div>
