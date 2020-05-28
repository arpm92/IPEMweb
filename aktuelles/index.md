---
layout: default
---

# News auf LinkedIn


<div> 
{% for item in site.data.aktuelles %}
    {% if item.active == true and item.type == 'linkedin' %}        
            <iframe src="{{ item.src }}" height="{{ item.height }}" frameborder="0" title="{{ item.title }}"></iframe>       
    {% endif %}
{% endfor %}
</div>
