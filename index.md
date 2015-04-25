---
layout: page
title: WetWorks
tagline: Crunching big data in ocean and climate sciences one byte at a time
---
{% include JB/setup %}

## Sample Posts

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Here is a comprehensive post list
<ul class="posts">
{% for post in site.posts %}	
    <h3><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="{{ BASE_PATH }}{{ post.url }}#disqus_thread"></a></small></p>			
{% endfor %}	
</ul>

