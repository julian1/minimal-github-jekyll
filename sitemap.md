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

tags don't work...

{% for tag in site.data.tags %}
  here {{ tag }}
{% endfor %}

