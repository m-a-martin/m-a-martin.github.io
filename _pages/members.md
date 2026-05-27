---
layout: archive
title: "Group members"
permalink: /members/
author_profile: true
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

    <p>{% if member.email %}
      <a href="mailto:{{ member.email }}">email</a>
    {% endif %} | {% if member.cv %}
      <a href="/files/cv/{{ member.cv }}">cv</a>
    {% endif %} | {% if member.gscholar %}
      <a href="{{ member.gscholar}} ">g. scholar</a>
    {% endif %}</p>
    
    {% if member.biography %}
    <p>{{ member.biography }}</p>
    {% endif %}
    
  </div>

  {% endif %}
{% endfor %}

</div>

{% endfor %}

*More to come.*
