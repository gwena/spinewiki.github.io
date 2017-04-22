---
layout: page
title : Needs
header : xcvbn
tagline: “From the perspective of _____, we are here to _____”
group : navigation
order : 1
---
{% include JB/setup %}

{% assign posts_collate = (site.posts | where: "category" , "Need") %}
{% include JB/posts_collate %}


<br>
*To learn about the "Needs" level of the Spine Model, go to [spinemodel.info/Needs](http://spinemodel.info/needs.html)*