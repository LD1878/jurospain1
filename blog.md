---
layout: default
title: Juro Spain Legal Guides & Blog
description: Expert articles and resources on obtaining Spanish residency, property law, visas, and living as an expat in Spain.
permalink: /blog/
---

# Your Resource for Spanish Legal & Expat Guides

<p>Welcome to our expert knowledge hub. Here you will find clear, up-to-date guides, news, and tips covering the critical legal and administrative aspects of moving to and living in Spain.</p>

---

{% assign sorted_posts = site.posts | sort: "date" | reverse %}

{% if sorted_posts.size > 0 %}
    
    {% for post in sorted_posts %}

    <div class="post-card">
        <a href="{{ post.url | relative_url }}">
            <h2>{{ post.title | escape }}</h2>
        </a>
        
        <p class="small" style="margin-bottom: 0.75rem;">
            Published: **{{ post.date | date: "%B %d, %Y" }}** {% if post.author %} | By: {{ post.author }} {% endif %}
        </p>
        
        {% assign raw_excerpt = post.excerpt | strip_html %}
        
        {% assign cleaned_excerpt = raw_excerpt | replace: "Table of contents", "" | replace: "table of contents", "" | replace: "Overview:", "" | strip | truncate: 180 %}
        
        <p>{{ cleaned_excerpt }}</p>

        <a href="{{ post.url | relative_url }}" class="btn" style="padding: 0.5rem 1rem;">
            Read Full Guide →
        </a>
    </div>

    {% endfor %}

{% else %}

<div class="card center">
    <h2>Content Coming Soon!</h2>
    <p>We are currently writing our first set of comprehensive guides and articles. Please check back soon!</p>
</div>

{% endif %}

---

## Need Legal Advice Now?

<p class="center">Don't wait for a blog post. If you have an urgent question about a visa, property purchase, or residency, book a free call.</p>

<div class="center">
    <a href="https://calendly.com/hello-jurospain/30min" class="btn" target="_blank" rel="noopener noreferrer">
        Book Your Free Consultation
    </a>
</div>
