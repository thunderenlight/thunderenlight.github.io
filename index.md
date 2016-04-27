---
layout: page
title: Welcome
tagline: 
---
{% include JB/setup %}

![My web dev journey]({{ site.url }}/assets/imgs/journey.png)

## A web dev's adventure begins: 

#### Stepping into the wild web...

Welcome to my DBC-blog : a Dev Boot Camp journey. This is where I will be journaling my technical and cultural DBC assignments as well. This is definitely an exciting opportunity to explore unknown technical territories. This is a very new and culturally stimulating space that is new to me and I feel more than lucky and excited to be a part of this adventure.

My goals include project-based learning of Ruby and ROR to build a skeleton web application that would support those that heavily mean independent on healthcare industry and being taken care of by others I'm excited about the ability to manipulate understand elements on an HTML been able to grasp a little bit about the dome of the DOM understand file structure outline structure and how it applies to not only the page structure the model of view and also the way that it exists on the server.

Hmmm, as for something culturally political...just recently started researching the Rand Corp. which helped solidify my opinions about the proprietorship of technology in blurring the world's geographical/political lines while creating and even embellishing digital divides...
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's my "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This site is still unfinished.

I need to clean up the site, and include piwik analytics and enable comments.
