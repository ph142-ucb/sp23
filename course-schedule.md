---
layout: page
title: Course Schedule
nav_order: 1
description: Weekly lectures and assignments.
---

# Course Schedule

**Please note:** This schedule is still tentative, and is likely to change. See the [calendar]({{ site.baseurl }}/calendar) to see the scheduling and Zoom links of our weekly events (lecture, lab, office hours, etc). [Here](https://docs.google.com/document/d/1kMlE5Mj7TKXc6_wygOg5qWdDV9_E38M1T513wDXwe_8) is the ongoing Q&A from lecture.


{% for module in site.modules %}
{{ module }}
{% endfor %}
