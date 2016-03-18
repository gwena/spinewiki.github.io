---
layout: page
title: Welcome to Spine Wiki
tagline: a free Spine Model catalog to which anyone can contribute
---
{% include JB/setup %}

## New to the Spine Model?
If you're not familiar with the Spine Model, we recommend you [learn the basic ideas behind the model first](http://spinemodel.info), before diving into this catalog.

## What is the purpose of this wiki?
The Spine Model can be applied to any human system and the individuals in it.

This wiki catalogs each level of the model and its various implementations in a way that creates an encyclopedia that anyone can draw from and [contribute to](https://github.com/SpineModel/spinemodel.github.io).

## Most recent contributions...
<ul class="posts">
  {% for post in site.posts limit:10 %}
    
    <!-- Add a dash if there is a tagline -->
    {% assign spacer = "-" %}
    {% if post.tagline == "" %}
        {% assign spacer = "" %}
    {% endif %}
    
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> ({{post.category}} by {{post.author}})</li>
  
  {% endfor %}
</ul>

<br>
<br>
<br>
<br>
