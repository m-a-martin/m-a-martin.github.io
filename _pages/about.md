---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<h1 align="center">
<em> We build quantitative models informed by molecular and epidemiological data to guide the public health response to emerging and endemic pathogenic threats.</em>
</h1>

The Martin Group @ JHU BSPH is a computational biology research group in the [Department of Epidemiology](https://publichealth.jhu.edu/departments/epidemiology) at the Johns Hopkins Bloomberg School of Public Health. Broadly, our work aims to reduce the global burden of infectious diseases. More specifically, we use pathogen molecular (particularly genomic) data and quantitative mathematical models to better understand the biological, environmental, and sociological drivers of pathogen population dynamics to inform the public health response to endemic and emerging infectious threats. We are a part of the [Infectious Disease Dynamics](https://www.iddynamics.jhsph.edu) group at JHU and collaborate broadly throughout the university and beyond. 

## Most of our work falls into one of the following themes: 

<div class="theme-grid">
  {% for theme in site.data.themes %}
    <div class="theme-card">
      {% if theme.name %}
        <h3> {{ theme.name }} </h3>
      {% endif %}
      {% if theme.image %}
        <img src="/images/themes/{{ theme.image }}" alt="{{ theme.name }}">
      {% endif %}
      {% if theme.description %}
        <p>{{ theme.description }}</p>
      {% endif %}
      {% if theme.publications %}
      <ul class="theme-publications">
        {% if theme.publications %}
        <b> Relevant publications:</b>
        {% endif %}
        {% for pub in theme.publications %}
          <li><a href="{{ pub.url }}">{{ pub.short-title }}</a></li>
        {% endfor %}
      </ul>
      {% endif %}
    </div>
  {% endfor %}
</div>

