---
layout: default
---


# Mitarbeiter des IPEM

## Leitung

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "faculty" and person.active == true %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Oberingenieur

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "oberingenieur" and person.active == true %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{site.baseurl}/team/{{ person.filename }}.html)<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Gruppenleiter

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "gruppenleiter" and person.active == true %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Sekretariat

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "secretary"  and person.active == true %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Wissenschaftliche Mitarbeiter

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "staff"  and person.active == true %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br>{{ person.team }}<br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Sprachdozenten

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "sprachdozenten"  and person.active == true %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br>{{ person.team }}<br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Externe Doktoranden

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "extphd"  and person.active == true %}
| ![img]({{site.baseurl}}{{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }}.html)<br>{{ person.team }}<br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Studentische und Wissenschaftliche Hilfskräfte

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "student" and person.active == true %}
| {{ person.fullname }}|{% endif %}{% endfor %}
{:width=50}


<br>

<!-- Commented area. Future ex PhDs 

## Ehemalige Mitarbeiter

| :--- |{% for person in site.data.team %}{% if person.status == "ex" %}| {{ person.fullname }} |{% endif %}{% endfor %}
{:width=50}

-->

<br>
{:class="w3-row"}
<br>


