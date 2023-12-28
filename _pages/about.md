---
layout: en
title: About
permalink: /about/
---

{% assign current_time = site.time | date: "%s" %}
{% assign birthdate = '1986-03-20' | date: "%s" %}
{% assign years_difference = current_time | minus: birthdate | divided_by: 31536000 %}

<div class="innerContent">
  <h4>About</h4>
  <p>
    I was born and raised in Istanbul. I am {{years_difference}} years old. I studied aquaculture at University of Istanbul. After completing my military service, I attended a web developer course and started working as a web developer in 2015.
    I've worked in several companies since then.
  </p>
  <p>I've developed mostly ASP.NET MVC projects. I also have experience with Angular projects.</p>
  <p>I have long-term plans to pursue a career as an AI developer.</p>
</div>
