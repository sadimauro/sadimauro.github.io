---
layout: page-fullwidth
#subheadline:  "Templates"
title:  "CMIA Halloween - 2008"
#teaser: "Wanna create a responsive gallery to showcase your portfolio, recent photos or images? It's quite easy thanks to Foundation and <a href='http://foundation.zurb.com/docs/components/clearing.html'>Clearing Lightbox</a>."
header:
   image: "various/sign1-crop-alternate-680x80.jpg"
   background-color:  "#ba8b3d"
categories:
    - gallery
#tags:
#    - post format
#image:
#   thumb: "unsplash_7_thumb.jpg"
---

<ul class="clearing-thumbs small-block-grid-3" data-clearing>
{% for i in (1..13) %}
  <li><a href="{{ site.url }}/images/2008-10-31-CMIA-halloween/{{ i }}.jpg"><img  data-caption="TODO" class="th" src="{{ site.url }}/images/2008-10-31-CMIA-halloween/{{ i }}_thumb.jpg"></a></li>
{% endfor %}
</ul>