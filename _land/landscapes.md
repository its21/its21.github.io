---
layout: post #this means it must be in a folder called _ocean
title: landscapes
#date: 2022-08-04 16:53:00
description: 
comments: true
category: 
importance: 1 #comes before ocean
image: /assets/img/land/boat_raja_ampat.jpeg
permalink: /land/landscapes/
---


<!-- 
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/1.jpg
    ---
-->

<div class="row justify-content-sm-center">
    <div class="col-sm-16 mt-3 mt-md-0">
        {% include figure.html path="assets/img/land/village_raja_ampat.jpeg" title="Misool" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm-16 mt-3 mt-md-0">
        {% include figure.html path="assets/img/land/boat_raja_ampat.jpeg" title="Misoo;" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="caption">
   Misool, Raja Ampat, Indonesia.
</div>
<!--
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above: -->
