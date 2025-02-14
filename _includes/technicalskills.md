| Machine Learning & Modeling |  |
| ---- | ---- |
{% assign skills = site.data.skills.mlstats -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}

| Programming | Level |
| ---- | ---- |
{% assign skills = site.data.skills.programming -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}

| Data Viz & Dashboards | Level |
| ---- | ---- |
{% assign skills = site.data.skills.datavis -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}

| Other | Level |
| ---- | ---- |
{% assign skills = site.data.skills.other -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}