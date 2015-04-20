---
layout: page-fullwidth
title: Photo Gallery
#subheadline: "TODO"
description: "Photo Gallery"
header:
   image: "various/sign1-crop-alternate-680x80.jpg"
   background-color:  "#ba8b3d"
permalink: "/gallery/"
---

{% for gallery in site.data.galleries %}
- [{{ gallery.description }}]({{ gallery.id }})
{% endfor %}