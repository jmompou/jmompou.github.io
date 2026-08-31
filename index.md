---
layout: splash
title: Home
permalink: /
---

{% capture cvcontent %}{% include_relative _pages/cv.md %}{% endcapture %}

{{ cvcontent | markdownify }}
