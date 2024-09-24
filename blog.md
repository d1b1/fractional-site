---
title: Fractional 101
layout: default
subtitle: Building a fractional consulting practice take time and effort.
order: 0
sitemap: false
---

{% include subStyles.css %}

{% assign programs = site.articles %}
{% for article in programs %}
  <div class="row">
 
    <div class="col-6 ">
      <h4>
        {{ article.title }}
      </h4>
      <!-- <span class="badge bg-success">Status: {{ article.status}}</span>
      <span class="badge bg-success">Stage: {{ article.stage}}</span> -->
    </div>
    <div class="col-6">
      {{ article.subtitle }}
      <a href="{{ article.url }}">read more...</a>
    </div>
  </div>
  <hr>
{% endfor %}

<style>
 hr { border: 1px solid #DFDFDF; }
</style>