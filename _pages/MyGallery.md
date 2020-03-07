---
layout: archive
title: "My Gallery"
permalink: /MyGallery/
author_profile: true
---

![](/images/atlantic.JPG) &nbsp; &nbsp; &nbsp; ![](/images/old main winter.JPG)
![](/images/old main sprng.JPG) &nbsp; &nbsp; &nbsp;  ![](/images/old main later spring.JPG)
![](/images/emodao.JPG) &nbsp; &nbsp; &nbsp; ![](/images/tangrenjie.JPG)
![](/images/netherland bikes.JPG) &nbsp; &nbsp; &nbsp;  ![](/images/netherland2.JPG)
![](/images/netherland.JPG) &nbsp; &nbsp; &nbsp; ![](/images/Movie/mfzybesj.JPG)
![](/images/psu xidian.JPG) &nbsp; &nbsp; &nbsp; ![](/images/star.JPG)
![](/images/monk.JPG) &nbsp; &nbsp; &nbsp;  ![](/images/chengdu3.JPG)
![](/images/chengdu view2.JPG) &nbsp; &nbsp; &nbsp; ![](/images/my hand in water.JPG)
![](/images/psu squirrel.JPG) &nbsp; &nbsp; &nbsp; ![](/images/psb hua.JPG)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
