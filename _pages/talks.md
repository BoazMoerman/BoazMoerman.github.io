---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% include base_path %}

<h1 class="archive__item-title" itemprop="headline">Research talks
</h1>
{% for post in site.talksresearch reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
<h1 class="archive__item-title" itemprop="headline">Learning seminar talks
</h1>
{% for post in site.talksseminar reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
