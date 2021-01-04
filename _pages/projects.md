---
layout: page
title: Projects
permalink: /jects/
description: My projects and projects I participated in.
nav: true
---

 {% comment %} #TODO: make jump-to fixed somewhere and always visible?{% endcomment %}
 
 {% comment %}
<style>
.project-filter {
  position: fixed;
  top: 57px;
  margin-left: auto;
  z-index: 1020;
  background-color: white;
  padding-top: 10px;
  margin-left: -20px;
  padding-left: 20px;
  margin-right: -20px;
  padding-right: 20px;
}
</style>

<div class="project-filter">sections: <a href="#services">apps & services</a>, <a href="#games">games</a>, <a href="#tools">tools</a> {% comment %}, <a href="#misc">misc</a></div> {% endcomment %} 
 
 {% endcomment %}
 
Jump to: <a href="#services">apps & services</a>, <a href="#games">games</a>, <a href="#tools">tools</a>{% comment %}, <a href="#misc">misc</a>{% endcomment %} 
 
{% comment %} https://stackoverflow.com/questions/10732690/offsetting-an-html-anchor-to-adjust-for-fixed-header {% endcomment %} 
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

{% comment %}
<h2 class="mt-4" id="misc">misc</h2>
***
{% assign sorted_projects = site.projects | sort: "importance" | where:"section","misc"%}
{% include project_grid.html %}

todo: uncomment when misc projects will be added (like music albums?)
{% endcomment %}
