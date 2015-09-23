---
layout: klassen
title: "Kleuterschool"
group: kleuters
permalink: /klassen/kleuters.html
--- 

<h2>Klassen - inline html</h2>
<ul>
{% for klas in site.data.klassen %}
  <li>
	<a href="{{ klas.href }}">
	  {{ klas.title }} xyz
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
