---
layout: page
title: IG-Comment Bot
description: Using generative AI to turn audience conversations into potential news coverage.
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

# Social Media Story Idea Tool

### The Task
Explore how generative AI could help journalists identify follow-up story opportunities from social media comments.

### The Problem
A social media post with high engagement can attract hundreds of comments. We needed a quick way to help busy journalists to identify useful audience insights and potential story ideas.

### The Context
At USA TODAY Co., we encouraged newsrooms to use audience analytics to better understand readers' interests and make data-informed decisions.

Beyond promoting content and driving traffic, social media comment sections offer newsrooms an opportunity to understand audience perspectives, identify unanswered questions, and source ideas for follow-up reporting.

However, online conversations can be a mixed bag. While some comment sections can be a gold mine for story ideas and crowdsourcing, others a filled with irrelevant, hostile, or abusive remarks. Given that newsrooms are active across several platforms and making several post a day, it was not  practical use of journalists' time to manually review comments across all platforms.

### The Solution
I developed **IG-Comment Bot**, a ChatGPT-based prompt designed to streamline the analysis of social media comments.

The tool was designed to, once given a URL, analyze comments associated with a social media post and share two things:

- **Audience sentiment score:** An estimated breakdown of positive, negative, and neutral comments.
- **Story ideas:** Potential follow-up reporting ideas informed by audience questions, concerns, and discussions.

The goal was to reduce the time spent manually reviewing comments while helping journalists identify traffic driving story opportunities.

### The Outcome
The tool attracted greater interest from the social media team than from reporters. Overall adoption among journalists was fairly limited.

Although the project demonstrated a potential application of generative AI in newsroom workflows, its reception highlighted an important consideration: **developing a tool that addresses a newsroom challenge does not guarantee that journalists will adopt it.**

The experience reinforced the importance of understanding users' existing workflows and professional needs when designing AI-assisted tools for journalism.


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

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

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
