---
layout: page-fullwidth
title: Search
header:
   image: "2014-06-01-around-CM/4_1600x315.jpg"
   background-color:  "#fafafa"
permalink: "/search/"
show_meta: false
---

{% include google_search.html %}

<form style="padding-bottom: 200px;" onsubmit="google_search()" >
  <input type="text" id="google-search" placeholder="{{ site.data.language.enter_search_term }}">
</form>
