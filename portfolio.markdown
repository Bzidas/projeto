---
layout: page
title: Cookies
permalink: /portfolio/
---

<h2 style="font-weight: 600;
  font-size: 1.313rem;
  text-transform: uppercase;
  text-align: left;">portfolio</h2>



{% for cookie in site.cookies %}

<section style="width:600px; margin:auto">

<div class="cookie">
<h2><img src="{{ cookie.image_path}}" alt="{{ cookie.title}}" />{{ cookie.title}} </h2>
{{ cookie.content }}
</div>

</section>

{% endfor %}


