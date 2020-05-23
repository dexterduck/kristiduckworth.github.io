---
title: 'Mosaics'
description: null
featured_image: '/images/gallery/mosaics/V8T3642.jpg'
---

<div class="gallery" data-columns="3">
    {% for image in site.static_files %}
        {% if image.path contains 'images/gallery/mosaics' %}
            <img src="{{ image.path }}">
        {% endif %}
    {% endfor %}
</div>