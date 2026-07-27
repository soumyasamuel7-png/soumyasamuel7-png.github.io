---
title: "Projects"
permalink: /projects/
layout: archive
author_profile: true
---

Hands-on data governance projects — click through to any project for the full write-up.

{% assign projects_sorted = site.projects | sort: "date" | reverse %}
<div class="entries-list">
  {% for post in projects_sorted %}
    {% include archive-single.html type="list" %}
  {% endfor %}
</div>
