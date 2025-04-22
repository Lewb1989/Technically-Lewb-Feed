---
layout: home
title: Welcome to Technically Lewb
---

![Technically Lewb Logo](/assets/images/logo.png)

## Latest Episodes

Check out the [RSS feed](https://lewb1989.github.io/Technically-Lewb-Feed/feed.xml)

---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*Posted on {{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}
---
{% endfor %}

