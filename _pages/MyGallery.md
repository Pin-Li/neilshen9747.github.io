---
layout: archive
title: "My Gallery"
permalink: /MyGallery/
author_profile: true
---

![](/images/atlantic.JPG) 

![](/images/Ontarioboys.JPG) 

![](/images/ontarioboys2.JPG) 

![](/images/emodao.JPG)

![](/images/tangrenjie.JPG)

![](/images/netherland bikes.JPG)

![](/images/netherland2.JPG)

![](/images/netherland.JPG)

![](/images/psu xidian.JPG)

![](/images/star.JPG)

![](/images/monk.JPG){:height="50%" width="50%"} &nbsp; ![](/images/chengdu3.JPG){:height="50%" width="50%"}

![](/images/my hand in water.JPG)

![](/images/psu squirrel.JPG)

![](/images/psu road.JPG)

![](/images/psb hua.JPG)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
