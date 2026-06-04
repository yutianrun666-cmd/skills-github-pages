---
title: Welcome to my blog!
---
## Daily study
- Learn Markdown
- Use GitHub

## Small code
```powershell
ffmpeg test
## 全部博文
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
