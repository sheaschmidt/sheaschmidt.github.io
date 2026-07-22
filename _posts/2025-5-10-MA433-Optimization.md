---
layout: post
title: Optimization and Optimal Control
subtitle: MA433 - Optimization 
thumbnail-img: /assets/img/Screenshot_20210629-183415_Instagram.jpg
tags: [Portfolio]

attachments: ma433
---

The following are documents produced for MA433 - Optimization

<iframe src="/assets/post_assets/ma433/Team_2_10_City_Optimization_Project.pdf" width="100%" height="1000px"></iframe>

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
