---
# the default layout is 'page'
icon: fas fa-info-circle
order: 5
title: "A Propos"
name: "A Propos"
permalink_en: /about/
permalink_fr: /a_propos/
---

{% if site.lang == "en" %}
    {% translate_file _tabs/about/about.md %}
{% elsif site.lang == "en" %}
    {% translate_file _tabs/a_propos/a_propos.md %}
{% endif %}