---
layout: post
# Required: used unconditionally as the page <h1> and index-card <h2>; empty or missing renders a blank heading.
# Required: post date, supplied by this file's YYYY-MM-DD-title filename (no separate `date:` front matter key needed here). Used unconditionally in the post header, meta line, and index date badge.
title:  "Welcome to JekyllMe"
date:   2016-02-16
---
JekyllMe is a free Jekyll theme for personal websites.

Your website includes a CV / resume, portfolio slideshow, blog and contact form, wrapped in a single page.

{% for experience in site.resume-items.experiences %}
  {{ forloop.index }}
{% endfor %}

[How to set up your website](/setup)
