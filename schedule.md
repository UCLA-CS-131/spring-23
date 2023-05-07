---
layout: page
title: Weekly Schedule
description: The weekly event schedule.
---

# Weekly Schedule

Runs from Week 1 - Week 10. OH are office hours!

Note: no lecture Week 9 Monday due to Memorial Day holiday (May 29th 2023)

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
