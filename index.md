---
layout: page
permalink: /
---


This Is The Website of Garuda. I write about Religion , Politics , Philosophy and Science.

For information about my site's design see this [post](https://garud.netlify.app/posts/exploring-the-features-of-enjoyment-work). For information about how to create a site using This theme , see this [post](https://enjoyment-work.netlify.app/posts/how-to-setup-enjoyment-work).

Pages you may like to visit:

- [Catalogue of Notes](https://garud.netlify.app/notes)
- [Journal](https://garud.netlify.app/journals)
- [Blog](https://garud.netlify.app/posts)


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

