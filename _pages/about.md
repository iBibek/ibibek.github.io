---
permalink: /
title: "Bibek Upadhayay"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


======

I am a Ph.D. candidate at the University of New Haven, currently researching the robustness and safety of multilingual LLMs.


### Recent Publications
<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}