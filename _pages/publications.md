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


## 2024

- Zhiyuan Hu, Chumin Liu, **Yue Feng**, Bryan Hooi. PoetryDiffusion: Towards Joint Semantic and Metrical Manipulation in Poetry Generation. Proceedings of the 38th AAAI Conference on Artificial Intelligence (**AAAI**), 2024

## 2023

- **Yue Feng**, Yunlong Jiao, Animesh Prasad, Nikolaos Aletras, Emine Yilmaz, and Gabriella Kazai. Schema-Guided User Satisfaction Modeling for Task-Oriented Dialogues. Annual Meeting of the Association for Computational Linguistics (**ACL**), 2023

- Hossein A. Rahmani, Xi Wang, **Yue Feng**, Qiang Zhang, Emine Yilmaz, and Aldo Lipani. A Survey on Asking Clarification Questions Datasets in Conversational Systems. Annual Meeting of the Association for Computational Linguistics (**ACL**), 2023

- Jiarui Jin, Xianyu Chen, Fanghua Ye, Mengyue Yang, **Yue Feng**, Weinan Zhang, Yong Yu, Jun Wang. Lending Interaction Wings to Recommender Systems with Conversational Agents. Annual Conference on Neural Information Processing Systems (**NeurIPS**), 2023

- Zhiyuan Hu, **Yue Feng**, Anh Tuan Luu, Bryan Hooi and Aldo Lipani. Unlocking the Potential of User Feedback: Leveraging Large Language Model as User Simulators to Enhance Dialogue System. ACM International Conference on Information and Knowledge Management (**CIKM Short Paper**), 2023





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



