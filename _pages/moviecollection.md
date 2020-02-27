---
layout: archive
title: "Movie Collection"
permalink: /MovieCollection/
author_profile: true
---

![](/images/Movie/adedsh.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/Movie/ayzc.JPG){:height="33%" width="33%"}
![](/images/Movie/cgzx.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp;  ![](/images/Movie/dbs.JPG){:height="33%" width="33%"}
![](/images/Movie/cmbyn.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp; ![](/images/Movie/djtc.JPG){:height="33%" width="33%"}
![](/images/Movie/hbdmqst.JPG){:height="33%" width="33%"} &nbsp; &nbsp; &nbsp;  ![](/images/Movie/hygs.JPG){:height="33%" width="33%"}
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
