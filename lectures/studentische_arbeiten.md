---
layout: default
title: Studentische Arbeiten
---

# Studentische Arbeiten

---

# Abschlussarbeiten (Bachelor/ Master) und Studienarbeiten
 

Bewerbungen für Abschluss und Studienarbeiten sollen ein Motivationsschreiben, den Lebenslauf und relevante Zeugnisse enthalten. Ohne diese Dokumente kann eine Bewerbung nicht berücksichtigt werden.

Unsere aktuellen Ausschreibungen finden Sie unter [Aktuelles]({{ site.baseurl }}/career/)

Informationen zu Ablauf und Anforderungen der Abschluss- und Studienarbeiten finden Sie [hier]({{ site.url }}/lectures/download/180204_abschlussarbeiten_am_ipem_lehrstuhl_v3_gt.pdf)

---

# Individual Project (Master IPEM)
 

Vom IPEM-Institut betreute Individual Projects für IPEM-Master Studenten werden individuell, nach Rücksprache mit den Mitgliedern der Arbeitsgruppe vergeben.

---


# Studien- / Bachelor- / Masterarbeiten (SA/ BA/ MA)

<!-- 
- Aktuell sind keine Abschlussarbeit vakant
-->

<ul>
    {% for item in site.data.thesis %}
        {% if item.active == true and item.type == 'thesis' %}
            <li>
                <a href="{{ site.baseurl }}/career/download/{{ item.file }}">{{ item.fullname }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>
