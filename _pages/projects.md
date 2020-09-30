---
layout: page
title: projects
permalink: /projects/
description: My projects and projects I participated in.
nav: true
---

 {% comment %} #TODO: make jump-to fixed somewhere and always visible?{% endcomment %}
 
 <strong>Jump to:</strong> [games](#games), [tools](#tools), [misc](#misc)
 
<h2 class="mt-4" id="services">apps & services</h2>
***
{% assign sorted_projects = site.projects | sort: "importance" | where:"section","services"%}
{% include project_grid.html %}

<h2 class="mt-4" id="games">games</h2>
***
{% assign sorted_projects = site.projects | sort: "importance" | where:"section","games"%}
{% include project_grid.html %}

<h2 class="mt-4" id="tools">tools</h2>
***
{% assign sorted_projects = site.projects | sort: "importance" | where:"section","tools"%}
{% include project_grid.html %}

<h2 class="mt-4" id="misc">misc</h2>
***
{% assign sorted_projects = site.projects | sort: "importance" | where:"section","misc"%}
{% include project_grid.html %}


