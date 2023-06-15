---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Articles are in reverse chronological order (most recent first).

{% if author.googlescholar %}
  You can also find my work on <a href="{{author.googlescholar}}">Google Scholar</a>
  and <a href="https://arxiv.org/search/?query=Bishop-Van+Horn&searchtype=author">arXiv</a>.

  ---------------------------------
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}

  ---------------------------------
{% endfor %}
