---
layout: klassen
title: "Kleuterschool"
permalink: /klassen/kleuters.html
--- 

<h2>Klassen - inline html</h2>
<ul>
{% for member in site.data.klassen %}
{% for klas in site.data.klassen %}
  <li>
	<a href="https://github.com/{{ member.github }}">
	  {{ member.name }}
	<a href="{{ klas.href }}">
	  {{ klas.title }}
	</a>
  </li>
{% endfor %}
	
Includes the following variables for easy customization:

**Kleuterschool**

* $primary-color
* $secondary-color
* $complimentary-color
* $body-bg
* $body-font-color
