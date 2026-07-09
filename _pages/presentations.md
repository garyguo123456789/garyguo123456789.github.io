---
layout: archive
title: "Presentations"
permalink: /presentations/
author_profile: true
hide_title: true
---

{% include base_path %}

<div class="archive">
  {% assign cv = site.data.cv %}
  {% if cv.presentations.size > 0 %}
  <div class="cv-section">
    <h2>Presentations</h2>
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
  </div>
  {% else %}
  <div class="cv-empty-state">
    <p>No presentations listed.</p>
  </div>
  {% endif %}
</div>
