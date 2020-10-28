---
layout: page
title: Fb datafile
permalink: /fingerboards/
---

Here you can find the collection of fingerboards handmade by myself.

<div class='pages_container'>

{% for fb in site.data.fingerboards %}
<div class='card'>
	<h3>{{ fb.name }}</h3>
	<p class='fb_material'>{{ fb.materials }}</p>
	<img src='/img/{{ fb.img }}'>
</div>

{% else %}

<p>Anything found</p>

{% endfor %}

</div>