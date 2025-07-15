---
layout: home
author_profile: true
---

# Welcome to My Data Science Portfolio

## Featured Projects

{% assign featured_projects = site.projects | limit: 3 %}
{% for project in featured_projects %}
  <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
  <p>{{ project.excerpt }}</p>
{% endfor %}

[View All Projects](/projects/){: .btn .btn--primary}
