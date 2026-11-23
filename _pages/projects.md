---
layout: page
title: Research
permalink: /research/
description: Optical instrumentation, physiological measurement, and scientific computing. Each entry states what the project studies and what I did.
nav: true
nav_order: 1
---

<div class="research-list">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
    <article class="research-item{% if forloop.first %} research-item--lead{% endif %}">
      {% if forloop.first %}<p class="tag">Current project</p>{% endif %}
      <p class="kicker">{{ project.kicker }}</p>
      <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
      <dl class="brief">
        <dt>Studies</dt>
        <dd>{{ project.subject }}</dd>
        <dt>My contribution</dt>
        <dd>{{ project.contribution }}</dd>
      </dl>
      <p class="more"><a href="{{ project.url | relative_url }}" aria-label="Project details: {{ project.title }}">Project details <span aria-hidden="true">→</span></a></p>
    </article>
  {% endfor %}
</div>
