---
layout: page
title: Course Announcements
nav_exclude: false
description: A feed containing all of the class announcements.
---

# Announcements
{% comment %}
Announcements are stored in the `_announcements` directory and rendered according to the layout file, `_layouts/announcement.html`.
{% endcomment %}

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
