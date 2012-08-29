---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

##测试

测试次点击卡拉防*静电*卡萨防**静电**卡萨拉风

 	
## Sample Posts
	  	
This blog contains sample posts which help stage pages and blog data.
	  	
<ul class="posts">
	{% for post in site.posts %}
			<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>