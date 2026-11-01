---
layout: portfolio
title: "Publications"
permalink: /publications/
excerpt: "Publications by Dong-Hyun Hwang in computer vision, generative AI, and human-computer interaction."
---
<p class="list-intro">Research in computer vision, generative models, and human–computer interaction. <a href="https://scholar.google.com/citations?user=0t5tW88AAAAJ">Google Scholar ↗</a></p>
{% assign publications = site.publications | sort: 'date' | reverse %}
{% for post in publications %}
<article class="publication-row">
  <p class="publication-year">{{ post.date | date: '%Y' }}</p>
  <div><h2><a href="{{ post.url | relative_url }}">{{ post.title }} <span aria-hidden="true">↗</span></a></h2>
  <p class="publication-venue">{{ post.venue }}</p>
  {% if post.authors %}<p class="publication-authors">{{ post.authors }}</p>{% endif %}
  <div class="paper-links"><a href="{{ post.url | relative_url }}">Details</a>{% if post.paperurl and post.paperurl != '' %}<a href="{{ post.paperurl }}">Paper ↗</a>{% endif %}</div></div>
</article>
{% endfor %}

