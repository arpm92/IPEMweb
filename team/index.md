---
layout: default
---


# Mitarbeiter des UTS

## Leitung

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "faculty" %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Sekretariat

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "secretary" %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Wissenschaftliche Mitarbeiter

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "staff" %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Studentische Hilfskräfte

| :--- |{% for person in site.data.team %}{% if person.status == "student" %}
| {{ person.fullname }} |{% endif %}{% endfor %}
{:width=50}

<br>

## Ehemalige Mitarbeiter

| :--- |{% for person in site.data.team %}{% if person.status == "ex" %}
| {{ person.fullname }} |{% endif %}{% endfor %}
{:width=50}


<br>
{:class="w3-row"}
<br>
