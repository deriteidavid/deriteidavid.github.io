---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on my <a href="https://scholar.google.com/citations?user=kN1RTWkAAAAJ">Google Scholar profile</a>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
