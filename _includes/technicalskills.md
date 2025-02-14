| Machine Learning |  |
| ---- | ---- |
{% assign skills = site.data.skills.mlstats | sort: "title" -%}
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
{% assign skills = site.data.skills.datavis | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}