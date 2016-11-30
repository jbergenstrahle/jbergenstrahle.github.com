---
layout: page
title: Recent posts
---
{% include JB/setup %}

{% for post in site.posts %}
<div>
<h2>{{ post.title }}<br>
  <small class="chip">{{ post.date | date: "%b %-d, %Y" }}</small>
</h2>
		
<div class="post-content">
	{{ post.content }}
</div>
</div>
{% endfor %}
