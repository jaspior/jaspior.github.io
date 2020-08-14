---
layout: default
title: Jaspior
---

<div class="blurb">
	
	
	<h1> Rumo ao EUF 2020 </h1>
	
	 {% for post in site.posts %}
	    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}

	$$
	R_{\mu \nu} - {1 \over 2}g_{\mu \nu}\,R + g_{\mu \nu} \Lambda = {8 \pi G \over c^4} T_{\mu \nu} 
	$$
</div><!-- /.blurb -->
