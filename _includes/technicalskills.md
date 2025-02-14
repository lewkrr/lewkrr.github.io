| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.programming | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}