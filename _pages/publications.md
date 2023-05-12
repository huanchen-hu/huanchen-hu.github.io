My referred papers are listed in [this ADS library](https://ui.adsabs.harvard.edu/user/libraries/F-uwfqs5SweTjz3cFKtoSg)
To be updated...

---
layout: archive
title: "Thesis"
permalink: /thesis/
author_profile: true
---

---
layout: archive
title: "Leading author papers"
permalink: /leadpapers/
author_profile: true
---

---
layout: archive
title: "Collaboration papers"
permalink: /copapers/
author_profile: true
---

---
layout: archive
title: "Books"
permalink: /books/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
