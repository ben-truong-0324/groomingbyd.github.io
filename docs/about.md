---
layout: default
title: About Deanna
permalink: /about/
---

{% include philosophy.html %}
{% include qualifications.html %}

{% include poster-services.html %} 

<section class="final-cta" style="text-align: center; padding: 40px 5%; background: var(--soft-pink);">
    <div style="display: flex; gap: 15px; justify-content: center; flex-wrap: wrap;">
        <button class="testimonial-btn" onclick="document.getElementById('qualifications').scrollIntoView({behavior: 'smooth'})">
            <i class="fas fa-award"></i> See Qualifications
        </button>
        <a href="/groomingbyd.github.io/pricing" class="testimonial-btn" style="text-decoration: none;">
            <i class="fas fa-tags"></i> See Services & Pricing
        </a>
    </div>
</section>
