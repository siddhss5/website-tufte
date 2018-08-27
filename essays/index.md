---
layout: full-width
title: Essays
---
**[es·say](https://en.wikipedia.org/wiki/Samuel_Johnson)** _"A loose sally of the mind; an irregular undigested piece; not a regular and orderly composition."_

{% for post in site.posts %}      
### [{{ post.title }}]({{ post.url | prepend: site.baseurl }}) 
{{ post.date | date: "%B %-d, %Y" }}
  {{ post.excerpt }}
{% endfor %}
