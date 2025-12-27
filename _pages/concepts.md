---
title: concepts
---




{% assign concepts = site.concepts %}

{% for concept in concepts %}
<article class="archive-item">
	<h5><a href="{{ site.baseurl }}{{ concept.url }}">{{concept.title}}</a></h5>
</article>
{% endfor %}