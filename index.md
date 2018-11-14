---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Welcome to the {{ site.title }}!

UDM: [link to UDM](https://coursepress.lnu.se/program/utveckling-och-drift-av-mjukvarusystem/)

<ul class="course-list">
{% for course in site.pages %}
  {% if course.courseCode %}
  <li title= "{{ course.courseName }}">
      <a href= "{{ course.url }}">{{ course.courseCode }}</a>
  </li>  
  {% endif %}  
{% endfor %}
</ul>
