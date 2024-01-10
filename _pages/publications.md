---
title: "Smith Lab - Publications"
layout: homelay
excerpt: "Smith Lab -- Publications."
sitemap: false
permalink: /publications/
---

<div class="container-fluid our-team">
<section class="container">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 x-p">
<h1 class="w-txt">Publications</h1>
<p class="a7-w-txt">Discover the Depth and Breadth of Our Academic Endeavors Through an Extensive Collection of Publications</p>
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
<div class="bx recent-bx">
<a href="{{ publi.link.url }}">
<div class="media">
<!-- Image can be included here if needed -->
<!-- <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" width="225" height="225" alt="{{ publi.title }}"> -->
</div>
<div class="info">
<h3 class="title">{{ publi.title }}</h3>
<h5 class="sub-txt">{{ publi.author }} {{ publi.source }} ({{ publi.year }})</h5>
</div>
</a>
</div>
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

