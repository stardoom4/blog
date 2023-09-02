---
layout: page
permalink: /
---


This Is The Website of Garuda. I write about Religion , Politics , Philosophy and Science.

Pages you may like to visit:

- [Catalogue of Notes](https://celestialentity.netlify.app/notes)
- [Journal](https://celestialentity.netlify.app/journals)
- [Blog](https://celestialentity.netlify.app/posts)


## Archive
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

