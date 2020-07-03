---
layout: default
title: Karriere  | IPEM
---

## Stellenangebote

---

# Wissenschaftliches Personal / Administratives Personal

- Aktuell sind keine PEP-Projekte vakant

<ul>
    {% for item in site.data.position %}
        {% if item.active == true and item.type == 'wimi' %}
            <li>
                <a href="{{ site.baseurl }}/career/download/{{ item.file }}">{{ item.fullname }}</a>
            </li>
        {% endif %}
        
    {% endfor %}
</ul>

---

# Studentische / Wissenschaftliche Hilfskräfte 

- Momentan keine Stelle vakant. Wir freuen uns auf Ihre Initiativbewerbung.

<ul>
    {% for item in site.data.position %}
        {% if item.active == true and item.type == 'shk' %}
            <li>
                <a href="{{ site.baseurl }}/career/download/{{ item.file }}">{{ item.fullname }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>

---

# Studentische Arbeiten 
- Bewerbungen für studentische Arbeiten sollen ein Motivationsschreiben, den Lebenslauf und relevante Zeugnisse enthalten. Ohne diese Dokumente kann eine Bewerbung nicht berücksichtigt werden.

---

# PEP-Projekte

- Aktuell sind keine PEP-Projekte vakant

<ul>
    {% for item in site.data.thesis %}
        {% if item.active == true and item.type == 'pep' %}
            <li>
                <a href="{{ site.baseurl }}/career/download/{{ item.file }}">{{ item.fullname }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>