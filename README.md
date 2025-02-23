A place to record projects, big 🚀 and small 🔋

## Main page
Shows links to all the projects, maybe a logo?

TODO: have projects on different pages

## Projects
* [**Flow Meter**](#flow-meter)
* [**Haptic Dial**](#haptic-dial)
* [**Cat Feeder**](#cat-feeder)
* [**Track Map**](#track-map)
* [**Time2Manage**](#time2manage)

---

## Flow Meter
Context:

<!-- ![](https://github.com/Your_Repository_Name/Your_GIF_Name.gif) -->
![](https://github.com/jkruiktech/Project-Hub/blob/main/assets/css/images/bucket_fill.gif)

##### add gif of testing the holding pressure of the relay switch

##### add gif/image of the other UI display screens and an explanation of what they're for 

## Haptic Dial
Context:
A Bluetooth dial able to connect to various media and provide analog-style control. Integration of haptics to allow feedback, and [reuse] in multiple applications with differing thresholds, min/max limits, and differing increments.
Could be used in a set of 3 to provide RGB colour control or PID control where haptics provide feedback of critical damping / perfected tuning, or in sound frequency equalisation. 

## Cat Feeder
Context:

## Track Map
Context:

[//]: <> (A physical formula 1 track able to display real time data from open source servers.)
This idea is the merging of 3D printed F1 track maps (which are reasonably widespread), and the small map shown during an F1 race. I wanted a physical display as a way of bringing the race closer. 

I made a plan (in a spreadsheet of course) and started collecting the necessary information to find out if it was possible. I thought maybe the data would be private or behind a paywall. So I looked at what was out there beyond the official FORMULA 1 apps and sites, whose information was under wraps. I discovered a few websites that displayed race analytics and even live maps of the race. They even used open source data! At that point I knew I was onto something. Seeing open source data displayed on a website with the cars moving around live, most likely meant I could do the same thing as a physical track.

###### MCU selection
Following this, I needed an MCU with wifi to access the data, GPIOs to control the LEDs, and a small footprint so it would fit easily within the design of the track. I also wanted it to be cheap and it didn't need a fast cpu/processor/clock speed due to not doing much

MCU selection - needed wifi, small footprint, quick setup - ESP32S3

###### Connecting to wifi


OpenF1 API - accesssing JSON data through selecting a url and using http get / fetch



### Project Repo: https://github.com/jkruiktech/TrackMap/tree/main/TrackMap_wifi

## Time2Manage

##### show figma image of the concept. explain the idea, who it's for, why they need it and why it was halted.

---

page for themes:
#### Tested Theme Hierarchy:
1. Minimal
2. Tactile
3. Minima
4. Architect
5. Dinky < CURRENT
6. Just-The-Docs

open it at: https://jkruiktech.github.io/Project-Hub/


