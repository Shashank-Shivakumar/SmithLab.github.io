---
title: "Smith Lab - Publications"
layout: gridlay
excerpt: "Smith Lab -- Publications."
sitemap: false
permalink: /publications/
---

<div class="container-fluid our-team">
<section class="container">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 x-p">
<h1 class="w-txt">Publications</h1>
<p class="a7-w-txt"><p class="a7-w-txt">Short description about the publications goes here and here also, short description about the research team goes here and here also.</p></p>
</div>
</section>
</div>

<div class="container-fluid">
<!-- Publication section starts here -->
<section class="container">
<div class="bx section-title-area">
<h2 class="section-title">Featured</h2>
</div>
<div class="bx recent-updates-list">
{% assign number_printed = 0 %}
{% for publi in site.data.publist %}
{% if publi.highlight == 1 %}
{% assign even_odd = number_printed | modulo: 2 %}
<a href="{{ publi.link.url }}" class="bx recent-bx">
<div class="media">
<img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" width="225" height="225" alt="{{ publi.title }}">
</div>
<div class="info">
<h3 class="title">{{ publi.title }}</h3>
<h5 class="sub-txt">{{ publi.author }} {{ publi.source }} ({{ publi.year }})</h5>
</div>
</a>
{% assign number_printed = number_printed | plus: 1 %}
{% endif %}
{% endfor %}
</div>
<div class="bx txt-a-c cta-wrapper">
<a href="#" class="btn btn-primary">See Complete List</a>
</div>
</section>
<!-- Publication section ends -->
</div>

