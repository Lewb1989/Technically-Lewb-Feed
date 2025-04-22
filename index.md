---
layout: home
title: Technically Lewb
---

![Logo](/assets/images/logo.png)

## Welcome to Technically Lewb

Your weekly dose of tech and gaming updates!  
Check out the [RSS feed](https://lewb1989.github.io/Technically-Lewb-Feed/feed.xml)

---

{% for post in site.posts %}
### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}
---
{% endfor %}
