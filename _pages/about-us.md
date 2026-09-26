---
permalink: /about-us/
title: "About our Foundation"
author_profile: false
layout: splash
---

## Who we are

### Our Board of Trustees

The M&M Cruz BEACON Foundation is guided by a dedicated Board of Trustees—a group of passionate community leaders, advocates,
and experts who donate their time, vision, and strategic oversight to our mission. Our Trustees ensure that every decision
we make advances sustainable growth, accountability, and meaningful impact for the communities we serve.

<!-- insert some grid here for the board -->
<div class="info-grid">
    {% for item in site.data.board-of-trustees %}
    <div class="info-item">
        <img src="{{ item.image | prepend: '/images/' | relative_url }}" style="max-width: 250px; width: 100%; height: auto;">
        <h3>{{ item.name }}</h3>
        <h4><em>{{ item.title }}</em></h4>
        <p>{{ item.bio }}</p>
    </div>
    {% endfor %}
</div>


## History and motivation

### Margaret's dream from a younger self

> My dream of transforming education started in high school with a vision of a modern, vibrant school filled with comfort, air-conditioned rooms, and great food spots. 
> While I still hold onto that vision, I’ve realized that creating meaningful change doesn't have to wait for bricks and mortar. 
> Deep down, what drove that dream was a firm belief that every student deserves a quality, supportive learning environment. 
> By focusing on scholarships and outreach today, we can immediately give underprivileged students the resources, access, and encouragement they need to thrive.

## What does BEACON stand for, and why does it represents our vision?

BEACON stands for **B**uilding **E**ducation, **A**dvocacy, and **C**ommunity **O**pportunities **N**ationwide. 
We believe that to truly empower a child, we must support them by combining educational scholarships with essential
health and community care. Just as a beacon shines through the dark to show the way forward, our mission is to serve
as the guiding light for the underprivileged youth, helping them navigate around financial and social barriers, so
they can reach their full potential.

## Core foundational pillars

With our vision as the goal, we aim to provide community-level support in each of the following four areas:

### Education and scholarship programs {#education-scholarship}

We provide financial assistance, tuition support, allowances, and learning materials to qualified, disadvantaged, 
marginalized, or orphaned student beneficiaries.

### Community-based outreach {#community-outreach}

We organize nutrition feeding programs in underserved areas. 

### Healthcare services {#healthcare-services}

Provide access to essential healthcare services, distribute medical supplies, and partner with medical
practitioners to deliver preventive and rehabilitative care to vulnerable children.

### Community development facilities {#community-development}

We also aim to support, build, or maintain community development facilitiies, transitional housing, or
safe spaces that provide secure shelter and holistic care for abandoned and neglected youth.
