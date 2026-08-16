---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<body>
  <iframe src="/files/Surya_Marimuthu_CV.pdf" width="100%" height="500px" marginwidth="0">

</body>

{% for post in site.CV %}
  {% include archive-single.html %}
{% endfor %}