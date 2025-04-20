---
layout: page
title: "All Books"
---

<div class="books">
  {% for book in site.books %}
    <div class="book">
      <h3>{{ book.title }}</h3>
      <img src="{{ book.image }}" alt="{{ book.title }} Cover">
      <p>{{ book.genre }}</p>
      <a href="{{ book.url }}">Read More</a>
    </div>
  {% endfor %}
</div>
