---
layout: default
cursesBA: "BA-MBD"
cursesMA: "MA-MBD"
---

# Vorlesungsangebot Maschinenbau (dual)

{% assign drawTableBAobligation = false %}
{% for lecture in site.data.lectures %} {% for curses in lecture.curses.obligation %}
  {% if curses == page.cursesBA %}
    {% assign drawTableBAobligation = true %}
  {% endif %}
{% endfor %}{% endfor %}
{% assign drawTableBAoption = false %}
{% for lecture in site.data.lectures %} {% for curses in lecture.curses.option %}
  {% if curses == page.cursesBA %}
    {% assign drawTableBAoption = true %}
  {% endif %}
{% endfor %}{% endfor %}


{% if drawTableBAobligation == true %}
## Bachelor
{% else %}
  {% if drawTableBAoption == true %}
## Bachelor
  {% endif %}
{% endif %}

{% if drawTableBAobligation == true %}
| Pflichtbereich | Semester  |
|:-------------- |:--------- |{% for lecture in site.data.lectures %} {% for curses in lecture.curses.obligation %}{% if curses == page.cursesBA %}
| [{{ lecture.fullname }}]({{ lecture.url }}){:target="_blank"} | {{ lecture.semester }} |{% endif %}{% endfor %}{% endfor %}
{:.lecturetablestyle}
{% endif %}

{% if drawTableBAoption == true %}
| Wahlpflichtbereich | Semester  |
|:-------------- |:--------- |{% for lecture in site.data.lectures %} {% for curses in lecture.curses.option %}{% if curses == page.cursesBA %}
| [{{ lecture.fullname }}]({{ lecture.url }}){:target="_blank"} | {{ lecture.semester }} |{% endif %}{% endfor %}{% endfor %}
{:.lecturetablestyle}
<br>
{% endif %}

{% assign drawTableMAobligation = false %}
{% for lecture in site.data.lectures %} {% for curses in lecture.curses.obligation %}
  {% if curses == page.cursesMA %}
    {% assign drawTableMAobligation = true %}
  {% endif %}
{% endfor %}{% endfor %}
{% assign drawTableMAoption = false %}
{% for lecture in site.data.lectures %} {% for curses in lecture.curses.option %}
  {% if curses == page.cursesMA %}
    {% assign drawTableMAoption = true %}
  {% endif %}
{% endfor %}{% endfor %}


{% if drawTableMAobligation == true %}
## Master
{% else %}
  {% if drawTableMAoption == true %}
## Master
  {% endif %}
{% endif %}

{% if drawTableMAobligation == true %}
| Pflichtbereich | Semester  |
|:-------------- |:--------- |{% for lecture in site.data.lectures %} {% for curses in lecture.curses.obligation %}{% if curses == page.cursesMA %}
| [{{ lecture.fullname }}]({{ lecture.url }}){:target="_blank"} | {{ lecture.semester }} |{% endif %}{% endfor %}{% endfor %}
{:.lecturetablestyle}
{% endif %}

{% if drawTableMAoption == true %}
| Wahlpflichtbereich | Semester  |
|:-------------- |:--------- |{% for lecture in site.data.lectures %} {% for curses in lecture.curses.option %}{% if curses == page.cursesMA %}
| [{{ lecture.fullname }}]({{ lecture.url }}){:target="_blank"} | {{ lecture.semester }} |{% endif %}{% endfor %}{% endfor %}
{:.lecturetablestyle}
{% endif %}

<br>
{:class="w3-row"}
<br>



