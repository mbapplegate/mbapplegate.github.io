---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
## Primary author
{% for post in site.publications reversed %}
  {% if post.firstauthor %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Co-author
{% for post in site.publications reversed %}
  {% if not post.firstauthor %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
