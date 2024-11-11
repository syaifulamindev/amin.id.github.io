---
layout: default
title: Home
permalink: /
---

# Welcome to amin.id

## About Me

Hello! I'm Syaiful Amin, an iOS developer passionate about creating innovative mobile applications and fostering community growth. Explore my journey in tech, freelancing experiences, and insights on iOS development. Head over to the [About Me](/about/) page for a more detailed story.

{% if site.posts.size > 0 %}
## Latest Articles

Discover the latest articles covering iOS development, freelancing tips, and community building:

{% for post in site.posts limit:3 %}
- **{{ post.title }}**
  - _Published on {{ post.date | date: "%B %-d, %Y" }}_
  - [Read →]({{ post.url }})
{% endfor %}

{% endif %}

## Let's Connect

Connect with me on various platforms:

- **LinkedIn:** [Syaiful Amin](https://www.linkedin.com/in/sayfullamin)
- **Twitter:** [@syaifulamindev](https://twitter.com/syaifulamindev)

Thank you for visiting, and I look forward to sharing more with you on this journey!
