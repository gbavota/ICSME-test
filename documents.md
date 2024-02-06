---
layout: page
permalink: /documents/
title: Documents
description: Official documents of the ICSME conference. You can contribute to them via pull requests on GitHub.
---

<ul class="post-list">
{% for document in site.documents %}
    <li>
        <h2><a class="poem-title" href="{{ document.url | prepend: site.baseurl }}">{{ document.title }}</a></h2>
        <p class="poem-meta">{{ document.last-revised | date last revision: '%B %-d, %Y' }}</p>
      </li>
{% endfor %}
</ul>