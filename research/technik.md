---
layout: default
title: Technik/Geräte  | IPEM
---

# Technik / Geräte

---

###### Der IPEM Lehrstuhl ist Teil des Instituts für Produktionstechnik. Das Verständnis für und der Umgang mit neuen Technologien ist ihm ein wichtiges Anliegen, daher stehen jedem Lehrstuhlmitarbeiter eine Vielzahl an Geräten zur Verfügung.

---

| :--- | :--- |{% for item in site.data.technik %}{% if item.status == true %}
| ![img]({{ item.image }}){:class="w2-container w3-card-4 w3-hover-opacity" width="{{ item.width }}" height="{{ item.height }}"} | **{{ item.fullname }}** <br><br> {{ item.description }} |{% endif %}{% endfor %}
{:width=50}