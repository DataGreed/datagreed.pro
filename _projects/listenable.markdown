---
layout: page
title: Listenable
description: Bite-sized audio courses created by renowned experts
img: /assets/img/projects/listenable/cover.png
importance: 1
---

<style>.full-width {
         width: 100vw;
         position: relative;
         left: 50%;
         right: 50%;
         margin-left: -50vw;
         margin-right: -50vw;
       }</style>

<div class="border-bottom full-width mt-5"></div>
<div class="container pt-3 pb-3">
  <div class="row">
    <div class="col pl-0">
      <div class="text-muted text-uppercase text-nowrap"><small><small>project type</small></small></div>
      <div><small class="font-weight-light">Educational Service</small></div>
    </div>
    <div class="col pl-0">
      <div class="text-muted text-uppercase text-nowrap"><small><small>platforms</small></small></div>
      <div><small class="font-weight-light"><a href="https://apps.apple.com/us/app/listenable-learn-via-audio/id1492810539" target="_blank">iOS</a></small></div>
      <div><small class="font-weight-light"><a href="https://listenable.io" target="_blank">Web</a></small></div>
    </div>
    <div class="col pl-0">
      <div class="text-muted text-uppercase text-nowrap"><small><small>my role</small></small></div>
      <div><small class="font-weight-light">CTO</small></div>
      <div><small class="font-weight-light">cofounder</small></div>      
      <div><small class="font-weight-light">software engineer</small></div>
    </div>
    <div class="col pl-0">
      <div class="text-muted text-uppercase text-nowrap"><small><small>time period</small></small></div>
      <div><small class="font-weight-light">Dec. 2019 – Present</small></div>
    </div>    

    
  </div>
</div>
<div class="border-top full-width mb-5"></div>

Listenable is an audio-based learning platform that helps you learn new things while doing something else.

todo: put the container above in yaml and render it automatically

todo: add platforms with links to corresponding pages

todo: as a part of a company Highbrow, inc

todo: would be great to add a distill-like header with platform with links, type (education service), time period, my role, platforms, etc.


## iOS App
***
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/listenable/ios1.png' | relative_url }}" alt=""/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/listenable/ios2.png' | relative_url }}" alt=""/>
    </div> 
    <div class="col-sm mt-3 mt-md-0">
            <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/listenable/ios3.png' | relative_url }}" alt=""/>
        </div>
        <div class="col-sm mt-3 mt-md-0">
            <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/listenable/ios4.png' | relative_url }}" alt=""/>
        </div>   
</div>
<div class="caption">
    Screenshots for iOS version of the Listenable App.
</div>

## Web App
***
todo: add screenshots 

## My Role

todo: analytics (inlcuding minutes), affiliate, etc, etc. programming, operations, monitoring etc, loadtesting api design when bootstrapping without any funding.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/" target="_blank">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
```
