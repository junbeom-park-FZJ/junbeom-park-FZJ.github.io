---
layout: page
permalink: /presentation/
title: Presentations
description: 
nav: true
nav_order: 5
---


<details open>
  <summary><b> A. Seminars and Lectures </b></summary>
  <ol>
  {% for paper in site.data.presentation_seminar %}
    <li>
      ({{paper.type}})  <b>{{ paper.title }}</b> <br>

      {% for author in paper.author %}
          {% if author.name == "Junbeom Park" %}
              <i> {{author.name}} </i>,
          {% else %}
              {{author.name}},
          {% endif %}
      {% endfor %}

      <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
    </li>
  {% endfor %}
  </ol>
</details>

<details open>
  <summary><b> B. Oral presentations at conferences </b></sumary>
  <ol>
  {% for paper in site.data.presentation_oral %}
    <li>
      <b>{{ paper.title }}</b> <br>

      {% for author in paper.author %}
          {% if author.name == "Junbeom Park" %}
              <i> {{author.name}} </i>,
          {% else %}
              {{author.name}},
          {% endif %}
      {% endfor %}

      <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
    </li>
  {% endfor %}
  </ol>
</details>


<details>
  <summary><b> C. Poster presentations at conferences </b></summary>
  <ol>
  {% for paper in site.data.presentation_poster %}
    <li>
      <b>{{ paper.title }}</b> <br>

      {% for author in paper.author %}
          {% if author.name == "Junbeom Park" %}
              <i> {{author.name}} </i>,
          {% else %}
              {{author.name}},
          {% endif %}
      {% endfor %}

      <br> {{ paper.location }} ({{ paper.year }}) {{ paper.city }} <br>
    </li>
  {% endfor %}
  </ol>
</details>