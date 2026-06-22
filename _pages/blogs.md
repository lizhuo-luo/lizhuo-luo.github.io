---
permalink: /blogs/
author_profile: true
stylesheets:
  - /assets/css/home.css
---

A space for notes, paper readings, and project log entries.

<div class="blog-list">
  {% if site.posts.size > 0 %}
    {% for post in site.posts %}
      <article class="blog-entry">
        <h3 class="blog-entry__title">
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </h3>
        <p class="blog-entry__meta">
          <em>{{ post.date | date: "%Y.%m.%d" }}</em>
          {% if post.tags.size > 0 %}
            &middot;
            {% for tag in post.tags %}<span class="blog-entry__tag">{{ tag }}</span>{% unless forloop.last %} {% endunless %}{% endfor %}
          {% endif %}
        </p>
        {% if post.excerpt %}
          <p class="blog-entry__excerpt">{{ post.excerpt | strip_html | truncate: 200 }}</p>
        {% endif %}
      </article>
    {% endfor %}
  {% else %}
    <p><em>No posts yet — check back soon.</em></p>
  {% endif %}
</div>
