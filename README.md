# {{ site.author }}

<p align="center">
  <a href="mailto:{{ site.email }}">{{ site.email }}</a> •
  {{ site.location }} •
  <a href="https://github.com/{{ site.github_username }}" target="_blank">GitHub</a> •
  <a href="{{ site.url }}{{ site.baseurl }}" target="_blank">Website</a>
</p>

---

## About Me

Welcome to my personal page! I am currently pursuing my Master's degree in Computer Science at the City University of Hong Kong. My interests lie primarily in machine learning, natural language processing, and computer graphics.

---

## Education

{% for edu in site.education %}
### {{ edu.degree }} in {{ edu.major }}
*   **Institution:** {{ edu.school }}
*   **Duration:** {{ edu.duration }}
*   **Key Coursework/Focus:** {{ edu.description }}
{% endfor %}

---

## Research Experience

{% for project in site.research %}
### {{ project.title }}
*   **Institution/Course:** {{ project.institution }}
*   **Duration:** {{ project.duration }}
*   **Description:** {{ project.description }}
{% endfor %}

---

<p align="center">
  <small>Powered by <a href="https://jekyllrb.com/" target="_blank">Jekyll</a> & <a href="https://github.com/pages-themes/minimal" target="_blank">Jekyll Theme Minimal</a></small>
</p>
