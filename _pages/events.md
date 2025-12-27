---
title: Events
layout: base
---
<main class="content">
  <section class="sleek-blog">
    <div class="container">
      <div class="sleek-post-list" itemscope="" itemtype="http://schema.org/Blog">
        {% assign events = site.events %}     
        {% for event in events %}
        {% include card_event.html %}
        {% endfor %}
      </div>
    </div>
  </section>
</main>
<div class="spacer"></div>
<div class="spacer"></div>