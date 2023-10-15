---
layout: archive
title: "Publications and Manuscripts"
permalink: /Research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

1. Zhang, Y., Xu, H., & Wang, W. (2020). [Preference robust models in multivariate utility-based shortfall risk minimization](https://www.tandfonline.com/doi/full/10.1080/10556788.2020.1827255?casa_token=55vjja42HfQAAAAA%3ASrZPv3BRuYZ02Zj8O0HMnig4RNDhv5XwiyT-O4KGa7lqauR56CjMUp3BRFiyOOfwQKxnGOUfhOwWvJs). Optimization Methods and Software, 37(2), 712-752.
