---
layout: post
title: ORBITAL DEBRIS IDENTIFICATION NETWORK
subtitle: AE427/AE445 - Preliminary/Detail Design of Spacecraft
thumbnail-img: /assets/img/AE427Thumbnail.png
tags: [Portfolio]

attachments: ae445
---

<iframe src="/assets/img/0001-1200.mp4" width="100%" height="450px"></iframe>
<iframe src="/assets/img/ODIN_Poster_3ftby2ft.pdf" width="100%" height="800px"></iframe>

{% assign folder = page.attachments %}

{% if folder %}
<hr>

## Downloads

<ul>
{% for file in site.static_files %}
    {% if file.path contains folder %}
    <li>
        <a href="{{ file.path }}">{{ file.name }}</a>
    </li>
    {% endif %}
{% endfor %}
</ul>

{% endif %}
