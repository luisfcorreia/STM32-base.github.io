---
title: "STM32F103RCT6 - Generic Board"
---

{% assign filename = page.name | remove: '.md' | remove: '.' %}
{% assign board = site.data.boards[filename] %}

{% include board-content.html data=board %}
