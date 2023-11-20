---
layout: archive
title: "Publications and Talks"
permalink: /publications/
author_profile: true
---

Selected Journal Articles (Peer-Reviewed)
=========================================


Selected Conference Proceedings and Talks (Peer-Reviewed)
==============================================


if author.googlescholar
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
endif

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
