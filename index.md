---
layout: page
title: The World As A Web Developer
tagline: 
---
{% include JB/setup %}

<div class="blog-list">
	{% for post in site.posts limit 5 %}
		<div class="blog">
			<div class="info">
				<a href="{{ post.url }}" class="title">{{post.title}}</a>
				<span class="date">{{post.date | date_to_string}}</span>
			</div>
			<div class="preview">
				<p>{{ post.content | strip_html | truncatewords:75}}</p>
				<a href="{{ post.url }}">Read more...</a>
			</div>
		</div>
	{% endfor %}
</div>

{% if site.posts.size > 5 %}
<a href="/archive.html">Full blog archive</a>
{% endif %}