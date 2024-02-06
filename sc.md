---
layout: page
title: Steering Committee
permalink: /sc/
---



{% for member in site.sc %}

<div class="project" style="margin-bottom:3em">
<a href="{{ member.website }}" target="_blank">
<img class="thumbnail" src="{{ member.picture }}"/>
<h1>{{ member.name }}</h1>
<h4>{{ member.affiliation }}</h4>
<h5>{{ member.role }}</h5>
</a>
</div>

{% endfor %}
