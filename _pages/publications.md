---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can find the full list of my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a> or in my resume.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
