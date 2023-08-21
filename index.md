---
layout: page
permalink: /
---

[![Netlify Status](https://api.netlify.com/api/v1/badges/734e4402-d8d0-42ea-bf25-dd67d3b8ae3b/deploy-status)](https://app.netlify.com/sites/garud/deploys)

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

## Attribution

This project is built on [**Enjoyment work**](https://github.com/brennanbrown/enjoyment-work) by [Brennan Kenneth Brown](https://github.com/brennanbrown) a simple yet highly functional jekyll-based theme that combines the best of different worlds. It is a minimal and distraction free theme that strives to provide maximum value all without holding back on any essential features that a user would benefit from or would desire for.
