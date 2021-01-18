---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: trie
---

{% include base_path %}

A list of all the posts and pages found on the site. 

{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  {% capture label %}{{ collection.label }}{% endcapture %}
  {% if label != written_label %}
  <h2>{{ label }}</h2>
  {% capture written_label %}{{ label }}{% endcapture %}
  {% endif %}
{% endunless %}

