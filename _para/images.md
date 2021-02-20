---
title: Images
permalink: /para/images.html
layout: para
---

## Images 


### Image the size of the text block


```{% raw %}{% include feature/figure.html objectid="SalmoPriest-CriticalHabitat-SalmoDivide535rim-IMAG0114" %}{% endraw %} ```

{% include feature/figure.html objectid="SalmoPriest-CriticalHabitat-SalmoDivide535rim-IMAG0114" %}

### Full page wide image

```{% raw %}{% include feature/figure-full-page.html objectid="SalmoPriest-CriticalHabitat-SalmoDivide535rim-IMAG0114" %}{% endraw %}```

{% include feature/figure-full-page.html objectid="SalmoPriest-CriticalHabitat-SalmoDivide535rim-IMAG0114" %}



### Options:

- "objectid" = The objectid of the object you'd like to feature . This is the last bit of the url for that item, minus the ".html"


<figure>{%- assign item = site.data[site.metadata] | where: "objectid", include.objectid | first -%}
    <label for="{{include.objectid}}" class="margin-toggle">&#8853;</label><input type="checkbox" id="{{include.id}}" class="margin-toggle"/><span class="marginnote"><a href="{{ '/item.html' | relative_url | append: '?id=' | append: item.objectid }}">{{ item.title }}</a>, {{ item.description | truncatewords: 5 }}</span> 
    
    <a href="{{ '/item.html' | relative_url | append: '?id=' | append: item.objectid }}"><img class="figure-img img-fluid rounded lazyload" alt="{{ item.description | escape }}" data-src="{% if item.youtubeid %}{{ 'https://img.youtube.com/vi/' | append: item.youtubeid | append: '/hqdefault.jpg' | relative_url }}{% else %}{{ item.image_small }}{% endif %}" {% if include.style%}style="{{ include.style}}"{% endif %}></a>
  </figure>