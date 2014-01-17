---
layout: default
title: Main
---


![](http://www.ricksteves.com/images/rail/railmaps/map_balkans.gif)

Latest in the blog
-------------------

<p>Blog RSS here: <a title="blog RSS" href="http://easterneurope.github.io/feed.xml">
                    <i class="fa fa-rss-square"></i></a></p>

<div id="posts">
    {% for post in site.posts offset: 0 limit: 3 %}
        <small style="color: #999;">{{ post.date | date: "%b %d, %Y" }}</small> 
        <a href="{{ post.url }}">{{ post.title }}</a>
        <br />
        {% if post.summary %}
            <small>{{ post.summary }}</small>
        {% endif %}
    {% endfor %}
    </div>




