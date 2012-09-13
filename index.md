---
layout: page
title: 学无止境
tagline: PKM&Sharing
---
{% include JB/setup %}

####*"Evernote做主要的知识管理，这里做轻量级的分享。"*	

---
<div class="row">
  <div class="span8">
  <h4>最新发布文章</h4> 	
<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
  </div>

  <div class="span4">
    <h4>Published</h4>
    <h4>Tags</h4>
  </div>

</div>
