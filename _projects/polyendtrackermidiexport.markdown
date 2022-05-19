---
layout: project
title: Poly Tracker MIDI Export
description: MIDI Exporter for Polyend Tracker projects & patterns
img: /assets/img/projects/polyendtrackermidiexport/cover.png
importance: 1
featured: false
show_header_logo: true
section: tools   # for project list page
project_type: Productivity Tool
my_role: 
    - reverse-engineering
    - developer
dates: Apr 2022
platforms: 
    - name: Web
      url: https://polyend-tracker-midi-export.onrender.com
    - name: GitHub
      url: https://github.com/DataGreed/polyendtracker-midi-export
---

This tool lets you convert [Polyend Tracker](https://polyend.com/tracker/) projects and pattern files to MIDI, so you can compose music
on the Tracker and then easily port it over to your favourite DAW to continue working on it.

## Background
***
While working on my [musical](https://synapsoid.net/) [projects](https://obgonsverhu.ru) I found myself using 
[Polyend Tracker](https://polyend.com/tracker/) as a 
sequencer for external synthesizers a lot. Most of the time I've recorded the audio to 101 Music's BlueBox to bring it 
later into Ableton for final arrangement and mixing. At this stage I found 
[lack of MIDI export](https://help.polyend.com/624837-Is-the-Polyend-Tracker-able-to-importexport-MIDI-files) in 
Polyend Tracker very limiting and decided to reverse engineer the Tracker's pattern and project files to convert them to MIDI.

As a result I've created a Python Library that converts project and pattern file and a simple webtool that lets
you drop in a zipped Tracker project and get your arrangement and patterns in MIDI format.

Most of my thought process when reverse engineering is 
[documented](https://github.com/DataGreed/polyendtracker-midi-export/blob/main/reverse-engineering/session%201/session1-notes.md) 
in the GitHub repository.

## Media
***
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/polyendtrackermidiexport/frames.png' | relative_url }}" alt=""/>
    </div>     
    

</div>
<div class="caption">
    Reversed-engineered frames of the patterns files
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/polyendtrackermidiexport/screenshot1.png' | relative_url }}" alt=""/>
    </div>     


</div>
<div class="caption">
    Screenshot of the webtool – just drop in your zipped project to convert
</div>





## Links
***

1. [Polyend Tracker MIDI Exporter Web Tool](https://polyend-tracker-midi-export.onrender.com)
2. [Polyend Tracker MIDI exporter Python Library Repo](https://github.com/DataGreed/polyendtracker-midi-export)


