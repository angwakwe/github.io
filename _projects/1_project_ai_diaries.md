---
layout: page
title: The AI Diaries
description: Exploring how undergraduate students and employers conceptualise and use GenAI
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

**Context**

In response to rising role of AI in various industries, teaching staff at the University of Surrey wanted to understand the skills employers expected from candidates. This information would inform redesigning curriculum and delivering lectures on topics that prepared students for their professional careers. 

To support the project, I analyzed over 3,500 job descriptions from the UK Job Board <Reed.co.uk> collected between May and July 2026. Using ChatGPT, I wrote a Python scripts to automate my analysis. To assess the accuracy of the script, I manually inspected the code output and job descriptions and iteratively refined the code to address any problems. 

The findings were translated into a formal report that were shared with faculty and I will be delivered as a teach seminar with my colleague in November 2026.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

To achieve this, I developed a systematic process to collect and analyze job descriptions for the most common roles students pursue after graduation. 

I used ChatGPT to help write Python scripts to automate my analysis, manually inspected the code output and job descriptions to assess the accuracy of the script, and iteratively refined the code to address any problems. 

**Outcome**
I developed a human-in-the-loop process to analyze 3,898 job descriptions within the project time-constraints. The findings were translated into a formal report that was shared with faculty and a teaching seminar that I will deliver with my colleague in November 2026. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

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

{% endraw %}
