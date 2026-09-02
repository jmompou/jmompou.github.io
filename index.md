---
layout: splash
title: Home
permalink: /
---

{% capture cvcontent %}{% include_relative _pages/cv.md %}{% endcapture %}
{% assign cv_parts = cvcontent | split: '---' %}
{% assign cv_body = cv_parts | slice: 2, 100 | join: '---' %}

{{ cv_body | markdownify }}
