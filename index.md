---
layout: page
title: 一步一步，向目标奔去...
---
{% include JB/setup %}


## 汲取自然万物的能量，坚定不移的去做你完成你的使命... 

    
    你也许会累，恢复，努力，恢复，努力...
   
    你要坚定自己的信念，相信你自己...
      
    勇敢的向前走，勇气会为你扫清前方的一切障碍...
      
	  
## 多思考，多行动起来，你会找到最好的方法...


##Update：
-------------

<ul class="posts">
{% for post in site.posts %}
<li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>; <span>{{ post.date | date_to_string }}</span> </li>
{{ post.excerpt }}
{% endfor %}
</ul>




