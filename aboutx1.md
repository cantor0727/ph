---
title: About6
layout: page
permalink: "/南海/"
---




{%- assign header_order = site.pages -%}
{% for i in (1..2) %}

<h3>{{i}}</h3>
{% for iterm in header_order %}

{% if iterm.order1==i %}
<h4>{{iterm.title}}</h4>
{% for j in (1..2) %}
{% if iterm.order2==j %}

<ul>
<li> {{iterm.order1}}</li>
<li> {{iterm.order2}}</li>
</ul>
{% endif %}
{% endfor %}

{% endif %}
{% endfor %}
{% endfor %}


