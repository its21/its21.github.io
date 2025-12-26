---
layout: page #this means it must be in a folder called _pages
title: Ocean life
permalink: /ocean/
description: data
nav: true #switch to true if u want to see it
nav_order: 2
display_categories: [Country, Nudis, Seahorses]
horizontal: false
published: true
---
<div class="grid">
{% assign items = site.ocean | sort: "importance" %}
{% for item in items %}
  <div class="card">
    <a href="{{ item.url }}">
      <img src="{{ item.image }}" alt="{{ item.title }}">
      <h3>{{ item.title }}</h3>
      <p>{{ item.category }}</p>
    </a>
  </div>
{% endfor %}
</div>
