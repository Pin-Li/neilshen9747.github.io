---
layout: archive
title: "My Gallery"
permalink: /MyGallery/
author_profile: true
---

![](/images/atlantic.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/old main winter.JPG){:height="33%" width="33%"}
![](/images/old main sprng.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp;  ![](/images/old main later spring.JPG){:height="33%" width="33%"}
![](/images/emodao.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/tangrenjie.JPG){:height="33%" width="33%"}
![](/images/netherland bikes.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp;  ![](/images/netherland2.JPG){:height="33%" width="33%"}
![](/images/Movie/jsc.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/Movie/mfzybesj.JPG){:height="33%" width="33%"}
![](/images/Movie/myfj.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/Movie/rs.JPG){:height="33%" width="33%"}
![](/images/Movie/skggp.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp;  ![](/images/Movie/sxastd.JPG){:height="33%" width="33%"}
![](/images/Movie/wrzx.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/Movie/xc.JPG){:height="33%" width="33%"}
![](/images/Movie/xfr.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/Movie/xtjz.JPG){:height="33%" width="33%"}


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
