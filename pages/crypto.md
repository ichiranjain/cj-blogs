---
layout: default
permalink: /crypto.html
---
{% assign posts = site.posts | where:"type", "crypto" %}

<ul>
{% for post in posts %}
<li>
<a href="{{ site.url }}{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
<ul>
