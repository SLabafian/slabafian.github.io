---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

At the Centre for Future AI, University of London, we host weekly events dedicated to exploring the cutting edge of artificial intelligence. Each session features:

-    A Specific Topic: In-depth discussions led by invited speakers who share their expertise.
-    AI News: A review of the latest developments and trends in the AI landscape.
-    Research Highlights: Key insights from recent studies and innovations in AI.
-    New AI Tools: Hands-on introductions to emerging tools and technologies.

This page provides a summary of each session, along with links to topics and tools discussed. I aim to keep it updated every Thursday following the event.

{% if site.talkmap_link == false %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
