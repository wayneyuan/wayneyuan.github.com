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
<iframe width="100%" height="50" class="share_self"  frameborder="0" scrolling="no" src="http://widget.weibo.com/weiboshow/index.php?language=&width=0&height=550&fansRow=2&ptype=1&speed=0&skin=1&isTitle=0&noborder=0&isWeibo=0&isFans=0&uid=1653411765&verifier=0c2cdcf8&dpc=1"></iframe>
  </div>

</div>
