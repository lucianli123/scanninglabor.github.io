---
layout: page
title: Centers
permalink: /centers/
---

<ul>
    {% for language in site.centers %}
        <li>
            <h2>
                <a href="{{ language.url | relative_url }}">
                    {{ language.title }}
                </a>
            </h2>

            <p>
                <i>{{ language.description }}</i>
            </p>
            <p>{{ language.excerpt }}</p>
        </li>
    {% endfor %}
</ul>