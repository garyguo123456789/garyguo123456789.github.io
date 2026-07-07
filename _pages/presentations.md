---
layout: archive
title: "Presentations"
permalink: /presentations/
author_profile: true
---

{% include base_path %}

<div class="archive">
  <h1>Presentations</h1>

  {% assign cv = site.data.cv %}
  {% if cv.presentations.size > 0 %}
  <ul class="cv-list">
    {% for talk in cv.presentations %}
    <li class="cv-item">
      <div class="cv-item-header">
        <div class="cv-item-title">{{ talk.name }}</div>
        <div class="cv-item-date">{{ talk.date | slice: 0, 4 }}</div>
      </div>
      <div class="cv-item-content">
        <div class="cv-item-subtitle">{{ talk.event }}</div>
        {% if talk.location %}
        <div class="cv-item-detail">{{ talk.location }}</div>
        {% endif %}
        {% if talk.description %}
        <div class="cv-item-detail">{{ talk.description }}</div>
        {% endif %}
      </div>
    </li>
    {% endfor %}
  </ul>
  {% else %}
  <p>No presentations listed.</p>
  {% endif %}
</div>
