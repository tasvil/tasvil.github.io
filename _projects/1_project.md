---
layout: page
title: Cognitive Distortion Bot
description: Assistant in analyzing and rethinking thoughts
img: assets/img/12.jpg
importance: 1
category: pet projects
related_publications: true
---

A trainer for detecting cognitive distortions and making rational responses to them in a telegram bot.

Cognitive distortions are the main source of "useless" emotional stress. There is a limited list of such cognitive distortions: catastrophizing, generalization, black-and-white thinking, and so on. The skill of detecting such cognitive distortions can be trained. That's why we created our project - a chatbot.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
</div>

How it works:
1⃣The bot provides educational information about cognitive biases so that the user understands how to use the bot.
2⃣The user shares a thought that worries him.
3⃣The bot analyzes the thought for cognitive biases and provides a brief summary of the analysis.
4⃣The bot helps the user reformulate the thought into a more realistic one.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
</div>

My responsibilities on the project were to help the bot distinguish jokes and nonsense from real thoughts that need to be analyzed.

- Wrote a prompt to help LLM separate thoughts from non-thoughts.
- Optimized the code for convenient temperature adjustment when setting up LLM.

