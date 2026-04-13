---
layout: page
title: Best Hikes
description: Hiking guidebook for Ithaca
img: assets/img/bestHikes_coverTrim.jpg
importance: 1
category: work
related_publications: true
---

<!---
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---
--->

Between December 2024 and April 2026, I collaborated with Myra Shulman from the Cayuga Trails Club to produce a hiking guidebook 
that features the 50 best hikes in and around Ithaca, New York. Using ArcGIS Pro and the Affinity design suite, I created 
user-friendly hiking maps for each of the routes in the greater Ithaca area.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bestHikes_treman.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bestHikes_danby.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bestHikes_limeHollow.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hiking maps of Robert H. Treman State Park (left), Danby State Forest (center), and Lime Hollow Nature Center (right),
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bestHikes_spread.png" title="Interior Spread" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Each hike is accompanied by a map, hike description, and useful tips for your journey.
</div>

<!---
You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.
--->

_Best 50 Hikes in and around Ithaca NY_ is available April 2026. Order your book today at the <a href="https://cayugatrailsclub.org/order-guidebook/">Cayuga Trails Club website</a>. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bestHikes_taughannock.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bestHikes_cover.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Explore Ithaca and the Finger Lakes region through the Cayuga Trail Club's newest guidebook.
</div>

## About the book
Explore diverse landscapes within a 30-minute drive of downtown Ithaca, New York. From peaceful woods and roaring waterfalls to dramatic gorges and sweeping countryside views, these 50 hikes offer something for every adventurer. Each route includes clear directions, mileage, difficulty ratings, information for accessing trails by bus, and brief insights into the region's natural and human history. Wheelchair-accessible routes are clearly identified where applicable. Whether you're seeking a casual family walk or a challenging full-day outing, this book helps you discover the natural beauty that makes Ithaca a true outdoor treasure. Published by the Cayuga Trails Club, whose members have explored, built, and hiked the region's trails for more than 60 years, this is the area's most comprehensive hiking guide.

## About the author
Myra Shulman grew up in California, hiking the Santa Monica Mountains and backpacking in the Sierra Nevada, developing a lasting interest in natural history and outdoor exploration. At sixteen, she decided to become an ecologist, fascinated by the interactions among organisms and the landscapes that shape ecosystems. After earning a PhD from the University of Washington, Myra taught ecology and evolutionary biology at UCLA and Cornell and conducted research on ecological interactions on coral reefs and ocean shorelines. Moving to Ithaca in 1997, she explored local trails while learning about northeastern forests and the geologic forces that shaped the Finger Lakes region. She and her husband, Jim Morin, have hiked the entire Finger Lakes Trail across New York State. Discovering that the Cayuga Trails Club built and maintains many local trails, Myra joined the club, working on trail projects and stewardship. Elected to the board in 2020, she has held leadership roles, led the TCAT-to-Trails program, contributed to IthacaTrails.org, and partnered with community groups to expand access to parks and trails. She continues to lead hikes, delve further into natural history, and work on trail projects and community access to nature. A New York City native, Russell Kwong is a 2025 graduate of Cornell University's Urban and Regional Studies program. His interests and experience include using spatial data and mapping to guide sustainable land use, understand disparities in environmental exposure, and to connect people with outdoor recreation opportunities. For this guide, Russell volunteered to use his GIS and design skills to create clear, user-friendly hike maps that support trip planning and on-the-ground navigation.

<!---
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```
--->

{% endraw %}
