---
layout: default
---


# Team UTS

## Head

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "faculty" %}
| ![img]({{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }})<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Office

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "secretary" %}
| ![img]({{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }})<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Technical Staff

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "staff" %}
| ![img]({{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }})<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

<br>

## Research Staff
### Process control and cyberphysical systems

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "phd-bending4.0" %}
| ![img]({{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }})<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

### Bending of tubes and profiles of metallic materials

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "phd-metal" %}
| ![img]({{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }})<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
{:width=50}

### Bending of tubes and profiles of fibre-reinforced thermoplastics

| :--- | :--- |{% for person in site.data.team %}{% if person.status == "phd-thermo" %}
| ![img]({{ person.image }}){:width="70"} | [{{ person.fullname }}]({{ person.filename }})<br><br> {{ person.tel }}<br>[{{ person.email }}](mailto:{{ person.email }}) |{% endif %}{% endfor %}
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
