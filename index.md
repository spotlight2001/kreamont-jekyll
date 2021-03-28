---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
  image: "/assets/images/kreamont_header.jpg"
  
---

{% capture notice-2 %}
### Hilf mir, es selbst zu tun. Hilf mir, ich selbst zu werden.
Maria Montessori (1870 – 1952)
{% endcapture %}
<div class="notice">{{ notice-2 | markdownify }}</div>


{% include feature_row_posts %}


<figure class="third">
{% for sponsor in site.data.sponsoren %}
    <img src="{{sponsor.image}}">
{% endfor %}
</figure>
