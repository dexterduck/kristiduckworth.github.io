---
title: 'Student Work'
description: null
featured_image: '/images/gallery/students/Katy-Nautilus.jpg'
---

<div class="gallery" data-columns="3">
    {% for image in site.static_files %}
        {% if image.path contains 'images/gallery/students' %}
            <img src="{{ image.path }}">
        {% endif %}
    {% endfor %}
</div>