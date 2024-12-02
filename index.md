---
layout: default
title: Home
---

# Welcome to Hackathon Notes

This site is powered by [GitHub Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/). Here you can find a collection of notes from our hackathon.

## 📚 Table of Contents

{% raw %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
{% endraw %}

## 📬 Get in Touch

If you have any questions or suggestions, feel free to [contact us](mailto:your-email@example.com).

© {{ site.time | date: "%Y" }} Your Name. All rights reserved.
