---
layout: default
---

# Studium

---

Project Management: Die Veranstaltungen Project Management I, Project Management III, Projektmanagement V sowie Projektmanagement Grundlagen I werden in diesem Wintersemester wieder als Blockveranstaltung stattfinden. Die Termine und Räume sind in Unisono zu finden. Die Belegphase ist ab sofort geöffnet und schließt am 4. Januar 2020.

# Prüfungen

- Generelle Informationen zu Prüfungen des [Departments Maschinenbau](http://www.mb.uni-siegen.de/pruefungsamt/?lang=de).

- Generelle Informationen zur Prüfungsanmeldung: [Neue Richtlinien zur An-/Abmeldung von Prüfungen](https://www.ipem.mb.uni-siegen.de/lehre/pdf/2010-12-02-muendliche-pruefungen.pdf)


# Unisono
[Was ist Unisono? - Erklärungsvideo der Universität Siegen](https://www.youtube.com/watch?v=Ugi3XyTmBOs&feature=youtu.be)

[What is Unisono? - Explanation video from the University of Siegen](https://www.youtube.com/watch?v=zDIJMgpVkeE&feature=youtu.be)


# Veranstaltungen im Sommersemester 2019

## Projectmanagement

<ul>
    {% for item in site.data.lectures %}
        {% if item.active == true and item.area == 'pm' %}
            <li>
                <a href="{{ item.url }}">{{ item.fullname }}</a> 
            </li>
        {% endif %}        
    {% endfor %}
</ul>

## Sprachen

### Französisch

<ul>
    {% for item in site.data.lectures %}
        {% if item.active == true and item.area == 'french' %}
            <li>
                <a href="{{ item.url }}">{{ item.fullname }}</a> 
            </li>
        {% endif %}        
    {% endfor %}
</ul>

### Spanisch

<ul>
    {% for item in site.data.lectures %}
        {% if item.active == true and item.area == 'spanish' %}
            <li>
                <a href="{{ item.url }}">{{ item.fullname }}</a> 
            </li>
        {% endif %}        
    {% endfor %}
</ul>