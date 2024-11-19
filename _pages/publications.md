---
layout: archive
title: "Featured Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}


{% if site.author.googlescholar %}
  <div class="wordwrap">Full list please find in <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}







<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->


