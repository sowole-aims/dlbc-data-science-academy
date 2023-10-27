---
layout: page
title: Assignments
description: A feed containing all of the class assignments.
---

# Assignments

{% for assignment in site.assignments %}
{{ assignment }}
{% endfor %}
