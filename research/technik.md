---
layout: default
---

# Der IPEM Lehrstuhl ist Teil des Instituts für Produktionstechnik. Das Verständnis für und der Umgang mit neuen Technologien ist ihm ein wichtiges Anliegen, daher stehen jedem Lehrstuhlmitarbeiter eine Vielzahl an Geräten zur Verfügung.

{% for item in site.data.technik %}{% if item.status == true %}
 **{{ item.fullname }}** <br>
  ![{{ item.fullname }}]( {{ item.image }}){:height="{{ item.height }}" width="{{ item.width }}"} <br> {{ item.description }}
  {% endif %}{% endfor %}
{:width=50}