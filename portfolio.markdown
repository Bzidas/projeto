---
layout: page
title: Portfolio
permalink: /portfolio/
---


<div class="container">
  <ul>
  {% for portfolio in site.portfolio %}
    <li>
      <article>
        <a href="#" class="topic">{{ page.skills}}</a>
        <h3>{{ portfolio.title}}</h3>
        <p>{{ portfolio.content }}</p>
     </article>
    </li>
    {% endfor %}
  </ul>
</div>









