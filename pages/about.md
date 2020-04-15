---
layout: page
title: About
description: Some description.
permalink: /about/
---

<img class="img-rounded" src="/assets/img/uploads/profile.png" alt="Thiago Rossener" width="200">

{% capture my_include %}{% include readme.html %}{% endcapture %}
{{ my_include | markdownify }}