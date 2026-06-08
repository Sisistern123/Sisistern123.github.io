---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of the pages and collections on this site. Search engines can also use the
[XML sitemap]({{ base_path }}/sitemap.xml).

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  <h2>{{ collection.label | capitalize }}</h2>
  {% for post in collection.docs %}
    {% include archive-single.html %}
  {% endfor %}
{% endunless %}
{% endfor %}
