---
layout: default
title: blog
permalink: /blog/
---

<div class="row listrecent">

{% for post in site.posts %}

        {% include postbox.html %}

{% endfor %}

</div>