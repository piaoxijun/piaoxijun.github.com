---
layout: page
title: 首页
tagline: 在路上
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>&raquo;<span>({{ post.date | date_to_string }}</span>)</li>
  {% endfor %}
  
</ul>


<br></br><br></br><br></br>



###我的选择
<a href="{{ github }}">My GitHub</a><br></br>

<a href="{{ BASE_PATH }}/index_b.html">原范例页面</a>