---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Welcome to the {{ site.title }}!

At the university education [Software Development and Operations (UDM)](https://coursepress.lnu.se/program/utveckling-och-drift-av-mjukvarusystem/) at Linnaeus University in Sweden, the students adopt a vast amount of useful tools. Choose the course of interest below to show the material. Note: The course name is shown when hover the buttons.

<ul class="course-list">
{% for course in site.pages %}
  {% if course.courseCode %}
  <li title= "{{ course.courseName }}">
      <a href= "{{ course.url }}">{{ course.courseCode }}</a>
  </li>  
  {% endif %}  
{% endfor %}
</ul>
