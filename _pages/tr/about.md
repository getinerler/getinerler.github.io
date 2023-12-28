---
layout: tr
title: Hakkında
permalink: /tr/hakkinda/
---

{% assign current_time = site.time | date: "%s" %}
{% assign birthdate = '1986-03-20' | date: "%s" %}
{% assign years_difference = current_time | minus: birthdate | divided_by: 31536000 %}

<div class="innerContent">
  <h4>Hakkında</h4>
  <p>
    İstanbul'da doğup büyüdüm. {{years_difference}} yaşındayım. İstanbul Üniversitesi Su Ürünleri Mühendisliği bölümünden mezunum. Askerlik görevim bitince web yazılımı üzerine bir kursa katıldım ve 2015'de web yazılımcısı olarak çalışmaya başladım. O zamandan beri çeşitli şirketlerde çalıştım.
  </p>
  <p>Ekseriyetle ASP.NET MVC projeleri geliştirdim. Angular ile de tecrübem var.</p>
  <p>Yapay zekâ alanında çalışma planlarım var.</p>
</div>
