---
layout: page
title: Display & Rant
tagline: Show and tell with opinionated adults
---
{% include JB/setup %}

{% assign latest_ep = site.categories.episode |first %}
<div class="jumbotron">
  <div class="container">
     <h1>Now Playing</h1>
     <p><a href="{{ latest_ep.url }}">{{ latest_ep.title }}</a></p>
  </div>
</div>

Display & Rant is a podcast from [Max Battcher][mjb] and [Jordan
Wages][jkw].

[jkw]: http://jordanwages.com
[mjb]: http://worldmaker.net

The show notes for each episode are collected as slides and the
recommended format is one synchronized with the slides. For those that
prefer old school audio and mainstream podcast software, you can
[subscribe to Display & Rant on iTunes][itunes].

[itunes]: http://dsplynrnt.com/itunes

{% assign latest_post = site.posts |first %}
Latest post: [{{ latest_post.title }}]({{ latest_post.url }})

<!-- vim: ai spell tw=72: -->
