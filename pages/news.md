---
layout: page-fullwidth
title: News
description: "Community News"
header:
   image: "various/sign1-crop-alternate-680x80.jpg"
   background-color:  "#ba8b3d"
permalink: "/news/"
breadcrumb: true
---

<ul>
    {% for post in site.categories.news %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>