---
layout: page
title: Events 
group: navigation
---
{% include JB/setup %}

<h2>All Events</h2>

{% for category in site.categories %} 
  <ul>
    {% assign pages_list = category[1] %}  
    {% include JB/pages_list %}
  </ul>
{% endfor %}
