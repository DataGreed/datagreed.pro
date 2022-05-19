---
layout: project
title: Grouping Tool
description: Productivity tool for Unity
img: /assets/img/projects/unitygroupingtool/cover.jpg
importance: 2
featured: false
show_header_logo: true
section: tools   # for project list page
project_type: Productivity Tool
my_role: 
    - designer
    - developer
dates: Jun 2019
platforms: 
    - name: Unity
      url: https://assetstore.unity.com/packages/tools/utilities/grouping-tool-147552    
---

Grouping Tool is an Editor Asset for Unity that can easily group GameObjects together right in the Unity Hierarchy Panel 
from the context menu or with a keyboard shortcut (Cmd+G on Mac or Ctrl+G on Windows).

By default objects are grouped into an empty GameObject.

Custom Prefab templates can be used to group objects together. 

## Background
***
While working on Holes Online {%comment%}todo: add link {%endcomment %} I was building a city level from lots of multi-storey buildings. Each building was 
composed of various blocks representing different floors, windows, roofs, etc. I've built building from this blocks 
and nested them under a group objects with several pre-defined components attached to it. 

At some point of my workflow I became frustrated with the lack of "Group objects" option in Unity, 
so I decided to look for existing solutions. I did not find anything that satisfied me, so I decided to create an asset
to speed up the workflow.

## Media
***
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/unitygroupingtool/1.png' | relative_url }}" alt=""/>
    </div>     
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/unitygroupingtool/3.png' | relative_url }}" alt=""/>
    </div>
     
</div>
<div class="caption">
    Screenshots of Grouping Tool UI
</div>





## Links
***

1. [Grouping Tool Unity Assset Store Page](https://assetstore.unity.com/packages/tools/utilities/grouping-tool-147552)
2. [Guide to Grouping Objects in Unity](https://datagreed.medium.com/grouping-objects-in-unity-2763cbba0ce7)


