---
layout: page-fullwidth
title: Photo Gallery
#subheadline: "TODO"
description: "Photo Gallery"
header:
   image: "2014-06-01-around-CM/4_1600x315.jpg"
   background-color:  "#fafafa"
permalink: "/gallery/"
breadcrumb: true
---

<ul>
    {% for post in site.categories.gallery %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
