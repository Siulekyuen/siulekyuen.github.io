---
name: 張三
---

張三是一位示例成員，擅長寫現代詩與短詩。

## 作品
以下為張三的詩歌作品：
{% assign poems = site.posts | where:"author","張三" %}
<ul>
  {% for post in poems %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
