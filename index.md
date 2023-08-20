---
layout: page
permalink: /
---

[![Netlify Status](https://api.netlify.com/api/v1/badges/734e4402-d8d0-42ea-bf25-dd67d3b8ae3b/deploy-status)](https://app.netlify.com/sites/garud/deploys)
### Collect. Connect. Create.

[[“The first step in blogging is not writing them but reading them.” <br><cite>--- Jeff Jarvis </cite>::lmn]]<mark>Hello There!</mark> This project began development in late 2023 and is intended to serve three purposes:[[“Blogging is to writing what extreme sports are to athletics: more free-form, more accident-prone, less formal, more alive. It is, in many ways, writing out loud.” <br><cite>--- Andrew Sullivan</cite>::rmn]]

1. [**Catalogue of Notes:**](/notes)
   - For note taking. I take notes on various different topics but now I will release them to Public.
2. [**Daily Progress Journal:**](/journals)
   - A weekly/daily/monthly journal to showcase some of my daily wins and loses.
3. [**A Blog:**](/posts)
   - Finally, a blog where I can write about Politics and astronomy without any problems.

## Archive
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
