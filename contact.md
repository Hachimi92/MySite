---
layout: page
title: Contact
permalink: /contact/
---
Vous pouvez me contacter
{% if page %}
  Bonjour {{ page.title }} !
{% endif %}
Le mot 'anticonstitutionnellement'
comprend {{ 'anticonstitutionnellement' | size }} lettres !
Nous sommes en {{ 'now' | date: "%Y" }}.
{% if page.title == "Hugo" %}
    Hello {{ page.author }} !
{% elsif page.title == "art" %}
    Bonjour maître !
{% else %}
    Who are you?
{% endif %}

{% for item in array %}
    {{ item }}
{% endfor %}

