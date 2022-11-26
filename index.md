---
layout: default
---
# Hi, I'm {{ site.author }}!

University of Plymouth alumni, working with [@Datatonic](https://datatonic.com/) in 2023.

This site uses my [`Cutwell/featherweight`](https://github.com/Cutwell/featherweight) theme.

{% capture contact %}{% include contact.md %}{% endcapture %}
{{ contact | markdownify }}

_Blog posts_
{% if site.compression.blogs and site.posts %}
<table>{% for post in site.posts %}<tr><td class="d">{{ post.date | date: "%B %e, %Y" }} >></td><td><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></td></tr>{% endfor %}</table>
{% endif %}