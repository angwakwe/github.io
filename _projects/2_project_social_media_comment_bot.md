---
layout: page
title: IG-Comment Newsroom Bot
description: Using generative AI to turn audience conversations into potential news coverage.
img: assets/img/ig-comment-bot.jpg
importance: 2
category: work
giscus_comments: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ig-comment-bot.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Image Credit: <https://metricool.com/social-media-bots/>
</div>

### The Task
Explore how generative AI could help journalists identify follow-up story opportunities from social media comments.

### The Problem
A social media post with high engagement can attract hundreds of comments. We needed a quick way to help busy journalists to identify useful audience insights and potential story ideas.

### The Context
At USA TODAY Co., we encouraged newsrooms to use audience analytics to better understand readers' interests and make data-informed decisions.

Beyond promoting content and driving traffic, social media comment sections offer newsrooms an opportunity to understand audience perspectives, identify unanswered questions, and source ideas for follow-up reporting.

However, online conversations can be a mixed bag. While some comment sections can be a gold mine for story ideas and crowdsourcing, others are filled with irrelevant, hostile, or abusive remarks. Given that newsrooms are active across several platforms and make several post on each, it was not  practical use of journalists' time to manually review comments across all platforms.

### The Solution
I developed **IG-Comment Bot**, a CoPilot-based prompt designed to streamline the analysis of social media comments.

The tool was designed to, once given a URL, analyze comments associated with a social media post and share two things:

- **Audience sentiment score:** An estimated breakdown of positive, negative, and neutral comments.
- **Story ideas:** Potential follow-up reporting ideas informed by audience questions, concerns, and discussions.

The goal was to reduce the time spent manually reviewing comments while helping journalists identify traffic driving story opportunities.

### The Outcome
The tool attracted greater attention from the social media team, while overall adoption among journalists was fairly small.

Although IG-Comment Bot offers a practical use-case of GenAI in newsrooms, the limited adoption by journalist highlights an important reality of technology adoption : **developing a tool does not guarantee that user will adopt it**. 

Rather than creating a solution to a challenge that users aren't asking to be addressed, building tools based on expressed pain points may lead to more adoption. 

The experience reinforced the importance of understanding users' existing workflows and professional needs when designing AI-assisted tools for journalism.
