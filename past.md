---
layout: page
title: Past Conferences
permalink: /past/
---


<ul class="post-list">
{% for edition in site.past reversed %}
    <li>
        <h2><a class="poem-title" target="_blank" href="{{ edition.website }}">{{ edition.name }}, {{ edition.location }}</a></h2>
        <p class="poem-meta">{{ edition.when }}</p>
        <p class="poem-meta"><b>General Chair(s):</b> {{ edition.gc }}<br>
        <b>Program Chair(s):</b> {{ edition.pc }}</p>
      </li>
{% endfor %}
</ul>

<!-- this is for the lightbox --> 
<script type="text/javascript" src="/js/lightbox.js"></script>
<link rel="stylesheet" href="/css/lightbox.css">