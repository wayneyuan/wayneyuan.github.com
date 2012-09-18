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
  <form action="/search/">
  <h4>搜索</h4>
  <p><input type="search" name="q" placeholder="输入关键词按回车搜索" /></p>
  </form>
  <h4>Follow me on <a href="https://github.com/wayneyuan">Github</a></h4>
  <h4>Follow me on <a href="http://weibo.com/wayneyuan">SinaWeibo</a></h4>
  <h4>版权申明</h4>
  <p><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/2.5/cn/" target="_blank" class="hide-target-icon" title="本站(博客)作品全部采用知识共享署名-非商业性使用-禁止演绎 2.5 中国大陆许可协议进行许可。转载请通知作者并注明出处。"><img alt="知识共享许可协议" src="http://i.creativecommons.org/l/by-nc-nd/2.5/cn/88x31.png" /></a></p>
  </div>

</div>
