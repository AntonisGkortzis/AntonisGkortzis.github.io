---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


## Security
<b>[VulinOSS: A Dataset of Security Vulnerabilities in Open-source Systems](https://antonisgkortzis.github.io/publications/MSR18)</b><br>
<b>Antonios Gkortzis</b>, Dimitris Mitropoulos, Diomidis Spinellis. <i>ACM Mining Software Repositories conference (MSR'18). <br>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
