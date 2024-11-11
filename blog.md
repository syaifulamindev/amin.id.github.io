---
layout: default
title: Blog
permalink: /blog/
---

# Welcome to the Blog

Explore articles, tutorials, and insights on iOS development, freelancing, and community building. Dive into the world of technology and join the conversation.

{% if site.posts.size == 0 %}
## Coming Soon

Stay tuned! We'll be sharing exciting content soon. Meanwhile, join our [Discord community](https://discord.com/invite/Tkr8TgqAqf) to connect with other enthusiasts.

{% else %}
## Latest Articles

{% for post in site.posts %}
- **{{ post.title }}**
  - _Published on {{ post.date | date: "%B %-d, %Y" }}_
  - [Read →]({{ post.url }})
  - Discuss on [Discord](https://discord.com/invite/Tkr8TgqAqf)
{% endfor %}

{% endif %}

---

Thank you for reading!

