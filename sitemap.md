---
title: Site map
layout: about
---

<!-- html comment, it's iterating the non post content only -->


{% for tag in page.tags %}
  <h3>  {{ tag }} </h3>
{% endfor %}


#### Static files

{% for file in site.static_files %}
- [{{ file.path }}]({{ file.path }})
{% endfor %}


#### Posts

<!-- note the post path is local path, so use post.url instead -->
{% for post in site.posts  %}
- [{{ post.path }}]({{ post.url }})
{% endfor %}

#### Tags

tags work - but only on post content ...
perhaps categories - might work across pages
Or else - we structure everything as a post, and maybe also permalink?

{% for tag in site.tags %}
  here -> {{ tag | first }}

  {% for post in site.posts %}

  {% endfor %}

{% endfor %}


#### Categories

categories don't seem to work in non-post content

{% for category in site.categories %}
  here -> {{ category | first }}
{% endfor %}

