---
layout: page
permalink: /
---


This is my Digital Garden where I will write about my thoughts and The things I am have learned. You may want to check the Index page for all of my notes. Or start from [About me and this site](/about)




<hr>
{% for collection in site.collections %} 
 {% if collection.label != "pages" %} 
  
   <h2>Items from {{ collection.label }}</h2> 
   <ul> 
     {% for item in site[collection.label] %} 
       <li><a href="{{ item.url }}">{{ item.title }}</a></li> 
     {% endfor %} 
   </ul> 
   {% endif %} 
 {% endfor %}

