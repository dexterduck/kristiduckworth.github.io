---
title: 'Paintings'
description: null
featured_image: '/images/gallery/paintings/maineseashore.jpg'
---

<div class="gallery" data-columns="3">
    {% for image in site.static_files %}
        {% if image.path contains 'images/gallery/paintings' %}
            <img src="{{ image.path }}">
        {% endif %}
    {% endfor %}
</div>