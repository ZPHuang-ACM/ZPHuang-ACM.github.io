---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
A. Peer-reviewed Journal Papers
======
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

B. Peer-reviewed Conference Papers
======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
