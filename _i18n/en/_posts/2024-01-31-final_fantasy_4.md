---
layout: post
title:  "(WIP) Final Fantasy IV: Going a step further"
tags: final-fantasy
category: "Final Fantasy Marathon"
date: "2024-01-27"
lang: en
image:
  path: /assets/img/posts_preview_images/ff4_logo.jpg
  alt: Final Fantasy 4 Logo # or base64 URI
---

{% if site.lang == "fr" %}
  {% capture english_link %}{{ site.url }}/en{{ page.url }}{% endcapture %}
  <a href="{{ english_link }}" >{% t pages.english_article %}</a>
{% elsif site.lang == "en" %}
  {% capture french_link  %}{{ site.url }}{{ page.url }}{% endcapture %}
 <a href="{{ french_link }}" >{% t pages.french_article %}</a>
{% endif %}

> I played the game with x4 exp and gils
{: .prompt-info }