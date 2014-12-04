---
layout: page
title: 一切都会过去!
tagline: learn happy
---
{% include JB/setup %}


## 时间这个问题，最终还是个问题 

制定好自己的目标，然后去努力前进:
    
    你也会累
   
    你也许会迟疑
      
    勇敢的向前走
      
	  
灵魂在你人生的路上等你
    
## no pain no gain

行情这种东西，等你弄懂的时候你都已经不在了，所以就好好研究公司，研究品种，研究人...


文章列表：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




