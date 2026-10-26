---
layout: page
title: Projects
permalink: /projects/
description: Doctoral research, earlier work, and participation in a national research
  project.
nav: true
nav_order: 3
---

The projects below summarize my research experience and contributions. Each page describes the research topic, my role, and related work.

{% assign junbo_projects = site.projects | where: "junbo_project", true | sort: "importance" %}
{% for project in junbo_projects %}
<h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
<p><strong>{{ project.period }}</strong> · {{ project.role }}</p>
<p>{{ project.description }}</p>
<p><a href="{{ project.url | relative_url }}">Read project details →</a></p>
{% unless forloop.last %}<hr>{% endunless %}
{% endfor %}
