---
layout: page
title: 一切都会过去!
---
{% include JB/setup %}


## 坚定不移地去做正确的事情 

    
    你也会累
   
    你也许会迟疑
      
    勇敢的向前走
      
	  

    
## 不管前方有什么什么样的困难，关键是多思考，行动起来，你总会找到最好的方法...
   我们在任何时候都有选择的自由...


##Update：

<ul class="posts">
{% for post in site.posts %}
<li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>; <span>{{ post.date | date_to_string }}</span> &raquo</li>
<hr>
{{ post.excerpt }}
<hr>
{% endfor %}
</ul>




