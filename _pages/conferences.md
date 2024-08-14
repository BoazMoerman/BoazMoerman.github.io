---
layout: archive
title: "Conferences and seminars attended"
permalink: /conferences/
author_profile: true
---

{% include base_path %}

<h2 class="archive__item-title" itemprop="headline">Events organized
</h2>
{% for post in site.organized reversed %}
  {% include archive-single-conference.html %}
{% endfor %}

<h2 class="archive__item-title" itemprop="headline">Research visits
</h2>
{% for post in site.visits reversed %}
  {% include archive-single-conference.html %}
{% endfor %}

<h2 class="archive__item-title" itemprop="headline">Conferences attended
</h2>
{% for post in site.conferences reversed %}
  {% include archive-single-conference.html %}
{% endfor %}

<h2 class="archive__item-title" itemprop="headline">Seminars attended
</h2>
{% for post in site.seminars reversed %}
  {% include archive-single-conference.html %}
{% endfor %}
