---
layout: default
title: 首页
---

# 欢迎来到我的个人网站

你好！我是 AAAXY Bear，欢迎来到我的个人网站。

## 关于我

这里可以添加一些关于您自己的介绍。

## 最新文章

{% raw %}{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y年%m月%d日" }}
{% endfor %}{% endraw %}

## 联系方式

- GitHub: [aaaxy-bear](https://github.com/aaaxy-bear)
- Email: your-email@example.com
