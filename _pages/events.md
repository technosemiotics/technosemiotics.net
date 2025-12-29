---
title: Events
layout: base
---
<main class="content">
  <section class="sleek-blog">
    <div class="container">
      <div class="sleek-post-list" itemscope="" itemtype="http://schema.org/Blog">
        {% assign events = site.events | sort: 'start' %}     
        {% for event in events reversed %}
        {% include card-event.html %}
        {% endfor %}
      </div>
    </div>
  </section>
</main>
<div class="spacer"></div>
<div class="spacer"></div>