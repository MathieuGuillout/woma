---
layout: post
title:  "MushRooms"
date:   2016-07-20 10:21:09 -0400
image: /assets/mushrooms/b-09.png
categories: generative-art
---

{% for image in site.static_files %}
    {% if image.path contains 'mushrooms' %}
<img src="{{site.baseurl}}{{image.path}}" alt="{{image.path}}"/>
    {% endif %}
{% endfor %}
