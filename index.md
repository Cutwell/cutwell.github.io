---
layout: default
title: Zachary's Blog
---
# Hi, I'm Zachary.

Generative AI and Machine Learning Engineer working [@Datatonic](https://datatonic.com/).

{% capture contact %}{% include contact.md %}{% endcapture %}
{{ contact | markdownify }}

_Blog posts_
{% if site.compression.blogs and site.posts %}
<table>{% for post in site.posts %}<tr><td class="d">{{ post.date | date: "%B %e, %Y" }} >></td><td><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></td></tr>{% endfor %}</table>
{% endif %}
