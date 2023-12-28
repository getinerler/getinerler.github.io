---
layout: en
title: Home
permalink: /
---

{% assign current_time = site.time | date: "%s" %}
{% assign birthdate = '1986-03-20' | date: "%s" %}
{% assign time_difference = current_time | minus: birthdate %}
{% assign years_difference = time_difference | divided_by: 31536000 %}

<div id="home-div" class="innerContent">
    <br/><br/>
    <h2 class="black">Welcome to my page.</h2>
    <h3 class="dimgrey">I'm a full-stack web developer</h3>
    <h4 class="grey">and I plan to share articles here in the future.</h4>
</div>
