---
layout: page
title: 一切都会过去!
tagline: 锲而不舍，金石可镂
---
{% include JB/setup %}


## 时间这个问题，最终还是个问题 

制定好自己的目标，然后去努力前进:
    
    你也会累
   
    你也许会迟疑
      
    勇敢的向前走
      
	  
灵魂在你人生的路上等你
    
## no pain no gain

不管前方有什么什么样的困难，关键是多思考，行动起来，你总会找到最好的方法...
我们在任何时候都有选择的自由...


文章列表：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
<hr>
{{ post.excerpt }}
	<p> <a href="{{ post.url }}"><span >阅读全文 &raquo; </span></a></p>
<hr>
  {% endfor %}
</ul>




