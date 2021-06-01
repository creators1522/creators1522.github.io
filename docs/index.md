---
layout: default		
title: Home
---
<!-- 使用する＿layout以下のファイル名。この場合。_layout/default.html fontmatter内でコメントアウトできなく根？？？ -->
<!-- これ以下が{ {page,content} }で呼び出せる -->
# これが見出し1になるはず。
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>