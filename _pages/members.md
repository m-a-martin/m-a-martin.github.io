---
layout: archive
title: "Members"
permalink: /members/
author_profile: false
---
{% assign roles = "Principal Investigator" | split: "," %}

{% for role in roles %}

<h2>{{ role }}</h2>

<div class="members-grid">

{% for member in site.data.members %}
  {% if member.role == role %}

  <div class="member-card">
    {% if member.image %}
      <img src="/images/members/{{ member.image }}" alt="{{ member.name }}">
    {% endif %}

    <h3>
      {% if member.website %}
        <a href="{{ member.website }}">{{ member.name }}</a>
      {% else %}
        {{ member.name }}
      {% endif %}
    </h3>

    <p>{{ member.research }}</p>
    {% if member.email %}
      <p><a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
    {% endif %} <p>|</p>{% if member.cv %}
      <p><a href="/files/cv/{{ member.cv }}">{{ CV }}</a></p>
    {% endif %}
    
    {% if member.biography %}
    <p>{{ member.biography }}</p>
    {% endif %}
    
  </div>

  {% endif %}
{% endfor %}

</div>

{% endfor %}
