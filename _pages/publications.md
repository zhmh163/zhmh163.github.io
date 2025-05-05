---
layout: archive
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  Check our recent publications in [Google Scholar](https://scholar.google.com/citations?user=lGU7CGgAAAAJ&hl=zh-CN&oi=ao).
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
