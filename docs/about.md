---
layout: default
title: About Deanna
permalink: /about/
---

<section class="hero" id="about" style="background: #000; color: #fff;">
    <div class="hero-content">
        <h2 style="color: #FF69B4;">Expert Grooming for Your Best Friend.</h2>
        <p style="font-size: 1.2rem; margin-bottom: 25px;">Private, stress-free grooming with over 15 years of experience.</p>
        
        <div style="display: flex; gap: 10px;">
            <a href="https://groomer.io/booking/vacavillegroomingdepot" class="testimonial-btn" style="background: #FF69B4; color: #fff; text-decoration: none;">Book Now</a>
            <button class="testimonial-btn" onclick="document.getElementById('philosophy').scrollIntoView({behavior: 'smooth'})" style="background: #fff; color: #000;">Learn More</button>
        </div>
    </div>
    <div class="hero-image">
        <img src="{{ '/assets/images/gbd0.png' | relative_url }}" alt="Deanna Grooming">
    </div>
</section>


{% include philosophy.html %}
{% include qualifications.html %}

{% include poster-services.html %} 

<section class="final-cta" style="text-align: center; padding: 40px 5%; background: var(--soft-pink);">
    <div style="display: flex; gap: 15px; justify-content: center; flex-wrap: wrap;">
        <button class="testimonial-btn" onclick="document.getElementById('qualifications').scrollIntoView({behavior: 'smooth'})">
            <i class="fas fa-award"></i> See Qualifications
        </button>
        <a href="{{ '/pricing/' | relative_url }}" class="testimonial-btn" style="text-decoration: none;">
            <i class="fas fa-tags"></i> See Services & Pricing
        </a>
    </div>
</section>
