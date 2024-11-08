---
layout: home
title: Home
nav_exclude: false
nav_order: 0
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Administrivia
- Instructor: Nate Phillips
- Office hours: Tues/Thurs 3:15-4:15 PM & Wed 1-3 PM.  
				Also available by appointment and over Slack or Zoom.
- [Canvas page](https://rhodes.instructure.com/courses/7274): Use for grades, online assignment submissions, and assignment solutions.
- [Syllabus](syllabus/syllabus-231-f24.pdf) and [additional policies](syllabus/additional-policies.pdf).

## Resources
- : [**Assembly Language Textbook**](resources/assembly.pdf){: .label .label-reading }
- [Confluence](https://rhodescollege.atlassian.net/wiki/spaces/HPCL/pages/2661351440/Overview+of+the+Hardware+Lab+Environment): Guide for the Hardware Lab and Quartus
- [Digital](https://github.com/hneemann/Digital?tab=readme-ov-file): Simulator for digital logic and circuits
- [**NIOS II Simulator**](https://cpulator.01xz.net/?sys=nios-de2-115){: .label .label-lab } 
- [**NIOS II Reference Guide**](resources/NIOS II (Classic) Reference.pdf){: .label .label-reading } 

## Calendar
{% for module in site.modules %}
{{ module }}
{% endfor %}

