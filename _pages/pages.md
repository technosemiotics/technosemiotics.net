---
title: All pages
slug: /pages/
---
{% assign posts = site.pages %}
<ul>
  {%- for post in posts -%}
  <li>
      <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
  </li>
  {%- endfor -%}
</ul>