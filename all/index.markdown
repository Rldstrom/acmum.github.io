---
layout: default
title:  "All Posts"
author: Andrew Hood
date:   2013-11-24 12:32:42
lastedit: 2013-11-24 12:32:42
categories: website
---

All Website Posts
=================

<h3>Posts:</h3>
<ul class="posts">
	{% for post in site.posts %}
	<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>
