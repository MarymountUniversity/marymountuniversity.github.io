---
layout: archive
title: "HCI/XR/VR"
permalink: /hci/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.hci reversed %}
  {% include archive-single.html %}
{% endfor %}
