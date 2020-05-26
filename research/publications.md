---
layout: default
---

# Veröffentlichungen

---

<ul>
    {% assign sorted = (site.data.publications | sort: 'year') | reverse %}
    {% for item in sorted %}
    <li>
        <strong>{{ item.year }}</strong> -- {{ item.fullname }} : <strong>{{ item.title }}</strong> ({{ item.year }}) in: {{ item.in }}. {{ item.DOI}} {% if item.doc %}<a href="{{ site.baseurl }}/download/{{ item.doc }}">Download</a>{% endif %} {% if item.link %}<a href="{{ item.link }}">Original</a>{% endif %}
    </li>
    <br>
    {% endfor %}
</ul>