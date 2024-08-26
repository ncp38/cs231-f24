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
- [](https://rhodescollege.atlassian.net/wiki/spaces/HPCL/pages/2661351440/Overview+of+the+Hardware+Lab+Environment): Confluence guide for the Hardware Lab and Quartus
     

## Calendar
{% for module in site.modules %}
{{ module }}
{% endfor %}

