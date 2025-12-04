---
layout: default
title: Juro Spain Blog - Legal Guides and News for Expats
description: Latest articles and guides on Spanish visas, residency applications, property laws, and administrative tips for English-speaking expats.
---

<div class="wrapper fade-in py-4">
    <section>
        <h1>Legal Guides and News for Expats in Spain</h1>
        <p class="lead">Stay up-to-date with the latest changes in Spanish immigration, property law, and essential administrative processes. Our articles are written in plain English to help you move forward with confidence.</p>
    </section>

    <hr>
    
    <section class="post-listing">
        <h2>Latest Articles</h2>
        
        {% if site.posts.size > 0 %}
            <ul class="post-list" style="list-style: none; padding: 0;">
                {% for post in site.posts %}
                <li class="card">
                    <article>
                        <h3>
                            <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
                        </h3>
                        
                        <div class="post-meta" style="font-size: 0.9em; color: #777; margin-bottom: 0.5rem;">
                            <span style="font-weight: 700;">Published:</span> 
                            <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
                        </div>

                        {{ post.excerpt | strip_html | truncate: 200 }} 
                        
                        <p style="margin-top: 1rem;"><a href="{{ post.url | relative_url }}" class="btn" style="padding: 6px 12px; font-size: 0.9em;">Read More &rarr;</a></p>
                    </article>
                </li>
                {% endfor %}
            </ul>
        {% else %}
            <p class="text-center" style="padding: 2rem;">
                We are currently preparing our first batch of guides. Check back soon for expert advice on visas and property!
            </p>
        {% endif %}
    </section>

</div>
