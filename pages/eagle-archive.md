---
layout: page-fullwidth
title: Eagle Archive
#subheadline: "TODO"
description: "Past issues of The Eagle, the quarterly Carrollton Manor newsletter"
header:
   image: "various/sign1-crop-alternate-680x80.jpg"
   background-color:  "#ba8b3d"
permalink: "/eagle-archive/"
breadcrumb: false
---

{% assign seasons = "spring|summer|fall|winter" | split: "|" %}
{% assign years = "2015|2014|2013|2012|2011|2010|2009|2008|2007|2006|2005|2004|2003|2002|2001" | split: "|" %}

{% for yr in years %}
## {{ yr }} 
{% for season in seasons %}
<a href="/resources/eagle-archive/eagle-{{ yr }}-{{ season }}.pdf">{{ season | capitalize }}</a>
{% endfor %}
{% endfor %}