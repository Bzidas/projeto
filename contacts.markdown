---
layout: page
title: Contacts
permalink: /contacts/
---

<section class="contacto-content">

{% for meio in site.data.listacontactos %}
<div><h3>{{ meio.plataforma}}</h3> <a href="{{ meio.endereco }}">{{ meio.endereco }}</a></div>
{% endfor %}

</section>