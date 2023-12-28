---
layout: tr
title: Ana Sayfa
permalink: /tr/
---

{% assign current_time = site.time | date: "%s" %}
{% assign birthdate = '1986-03-20' | date: "%s" %}
{% assign time_difference = current_time | minus: birthdate %}
{% assign years_difference = time_difference | divided_by: 31536000 %}

<div id="home-div" class="innerContent">
    <br/><br/>
    <h2 class="black">Sayfama hoş geldiniz.</h2>
    <h3 class="dimgrey"> Full-stack web yazılımcısıyım.</h3>
    <h4 class="grey">Bu sitede zamanla yazılar paylaşmayı planlıyorum. </h4>
</div>