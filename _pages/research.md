---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## Working Papers
{% for post in site.research reversed %}
  {% if post.category == 'workingpaper' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Work in Progress
{% for post in site.research reversed %}
  {% if post.category == 'workinprogress' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Published Papers
{% for post in site.research reversed %}
  {% if post.category == 'publishedpaper' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
