---
layout: project
title: Holes Online
description: Multiplayer IO Game
img: /assets/img/projects/holesonline/cover.png
importance: 3
featured: false
show_header_logo: true
section: games   # for project list page
project_type: Indie Mobile Game
my_role: 
    - producer
    - developer
    - designer
dates: May 2019 – Aug. 2019
platforms: 
    - name: iOS
      url: https://apps.apple.com/us/app/holes-online/id1471777490
    - name: iPadOS
      url: https://apps.apple.com/us/app/holes-online/id1471777490    
---

Holes Online is a mobile game that lets you take control of a cartoony-looking hole and absorb various city objects 
like cars, vans, trees and buildings. The hole grows when consuming objects. You have become bigger than opponent 
holes to absorb them and win the match.

Features actual 4-player online multiplayer mode.

This game was my first (and quite successful) attempt at creating a multiplayer game with a low-level net code. 

## Background
***

Some In 2018-2019 [mobile IO games with fake multiplayer](https://www.youtube.com/watch?v=YCqnD40Q5T8&ab_channel=Miziziziz) were [on the rise](https://www.linkedin.com/pulse/mobile-gaming-fake-multiplayer-epidemic-jonathan-jungck/). One of this games was [Hole.io](https://en.wikipedia.org/wiki/Hole.io) by Voodoo.
The game took mechanics from Donut County and applied it to a multiplayer match inspired by Agar.io: you took control
of a literal hole in the ground that could move and tried to consume as much objects as you could moving through the 
city to become as big as possible and eventually consume all your opponents.

The game was quite fun and satisfying, but there was a catch: it was not actually a multiplayer game, but it tricked
you into thinking that it was one. You were actually playing with bots, but a lot of people just did not realize that.

I really liked the concept of the game and thought that it would be awesome if the game was actually multiplayer.
So I decided to build a similar game with a little different set of rules (classic deathmatch without time limits)
and better graphics (the city in Holes Online looks quite similar to the one in Hole.io because it uses the same 
asset pack from Synty Studios, although with different level of detail) and with actual multiplayer.

Unity lacked any built-in multiplayer solutions at the moment and I decided to build my own (for educational reasons).

I've used [Apple Game Center Realtime Multiplayer](https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/GameKit_Guide/Matchmaking/Matchmaking.html#//apple_ref/doc/uid/TP40008304-CH9-SW1)
 feature for matchmaking and data realtime exchange. 
 
Since I did not want to completely re-invent the wheel I've decided to recreate [Quake 3 Network Model](https://fabiensanglard.net/quake3/network.php)
for synchronizing state between clients since it's considered to be among the best ones.

All realtime data was serialized with [MsgPack](https://msgpack.org/index.html).

Surprisingly enough, implementing multiplayer was probably the smallest part of all work that was poured into the 
project – the level design and asset preparation consumed most of the project time.
Actual network interaction design and code took a couple of days, plus couple of days of testing. 
The multiplayer worked pretty well. 

I've also tried to release the game for Android utilizing Play Games Services multiplayer service (depricated as of 2020), but Google's SDK 
for Unity had a fatal flaw: players disconnected whenever the app focus was lost (e.g. when receiving a call or turning 
the device screen off), so the Android version was never published.
 
Ironically, most of the Holes Online players don't play multiplayer, but enjoy the single-player mode.


## Media
***
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/holesonline/1.png' | relative_url }}" alt=""/>
    </div>
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/holesonline/2.png' | relative_url }}" alt=""/>
    </div> 
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/holesonline/3.png' | relative_url }}" alt=""/>
    </div>
     
</div>

<div class="caption">
    <br>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/holesonline/4.png' | relative_url }}" alt=""/>
    </div>
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/holesonline/5.png' | relative_url }}" alt=""/>
    </div> 
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1 mh600" src="{{ '/assets/img/projects/holesonline/6.png' | relative_url }}" alt=""/>
    </div>
     
</div>
<div class="caption">
    Promotional Screenshots of Holes Online for iPad
</div>

{% comment %}
todo: add gameplay video
todo: add non-promo screenshots
todo: add screenshots of multiplayer lobby interface
{% endcomment %}







## Links
***

1. [Holes Online App Store Page](https://itunes.apple.com/ru/app/id1471777490)

