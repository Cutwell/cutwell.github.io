---
layout: default
title: Zachary's Blog
---
# Hi, I'm Zachary.

Machine Learning Engineer [@Datatonic](https://datatonic.com/) | [Partnered](https://www.langchain.com/partners) with [@LangChain](https://www.langchain.com/) and working on Generative AI.

{% capture contact %}{% include contact.md %}{% endcapture %}
{{ contact | markdownify }}

_Blog posts_
{% if site.compression.blogs and site.posts %}
<table>{% for post in site.posts %}<tr><td class="d">{{ post.date | date: "%B %e, %Y" }} >></td><td><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></td></tr>{% endfor %}</table>
{% endif %}
