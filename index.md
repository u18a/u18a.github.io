---
layout: home
---

# Welcome to the UDM Toolbox!

At the university programme *[Software Development and Operations (UDM)](https://coursepress.lnu.se/program/utveckling-och-drift-av-mjukvarusystem/)* at the Linnaeus University in Sweden, the students adopt a vast amount of useful tools. Choose the course of interest below to show the material. The course name is shown when hovering the buttons.

<ul class="course-list">
{% for course in site.pages %}
  {% if course.courseCode %}
  <li title= "{{ course.courseName }}">
      <a href= "{{ course.url }}">{{ course.courseCode }}</a>
  </li>  
  {% endif %}  
{% endfor %}
</ul>
