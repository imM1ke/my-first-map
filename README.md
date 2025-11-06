# My happy places

![](img/My_happy_places.png)

## What did I build?

["my happy places" App](imm1ke.github.io/my-first-map/)  is a one-page, web app that offers  the different places i went to, it has red points around Oakland showing where i went. 

Users can...
1. **Explore each map** by using gestures to zoom in/out anywhere, rotate the map orientation, or change the pitch (angle).
1. **See detailed about the places** (including where and why i was there) by clicking the on red point.

Here's a demo:
<img src="img/giphy.gif" alt = "Demostration of how to use my map and interact with the points" >

## Why did I build this?

i decided to build this because i wanted to remember about the places i went over the summer because i tend to forget and it will help with remebering, if someone ever ask i can also look back and rememeber our even send them this project.


## Tech stack

To build this app, I used the following tools:

1. [Google My Maps](https://www.google.com/maps/d/u/0/), for generating the route lines, and exporting the geometries in `KML` format.
2. [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/guides) library, for styling and displaying maps and route lines, and adding camera behaviors (flyto animations).
4. [Visual Studio Code](https://code.visualstudio.com/download) free IDE, with [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) and [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) extensions.
5. [GitHub pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site), for publishing the app for free!

## Code Spotlight
![](img/carbon%20(1).png)
One part of the code that i struggled with that i want to feature is. 

**The Coords** 

I struggled with this because i didnt in which order to put it in. And didnt know the coords had to go in a specific way. it took it while to figure out because i kept trying and finally figured out that i had to put them in the oppisite way so in the code the 37.82 had to go in the back and the -122.18 had to go in the front.
