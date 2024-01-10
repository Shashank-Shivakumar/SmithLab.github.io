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

{% for publi in site.data.publist %}
{% if publi.highlight == 1 %}

<div class="bx recent-bx">
<!-- <a href="{{ publi.link.url }}"> -->
<div class="media clickable-div" data-href="{{ publi.link.url }}">
<img src="{{ site.baseurl }}/images/pubpic/{{ publi.image }}" width="225" height="225" alt="{{ publi.title }}"> 
</div>
<div class="info clickable-div" data-href="{{ publi.link.url }}">
<h3 class="title">{{ publi.title }}</h3>
<h5 class="sub-txt">{{ publi.display }}</h5>
</div>
<!-- </a> -->
</div>
{% endif %}
{% endfor %}
</div>
<div class="bx txt-a-c cta-wrapper">
<a href="#" class="btn btn-primary">See Complete List</a>
</div>
</section>
<!-- Publication section ends -->
</div>

<script>
document.addEventListener('DOMContentLoaded', (event) => {
document.querySelectorAll('.clickable-div').forEach(div => {
div.addEventListener('click', function() {
window.location.href = this.getAttribute('data-href');
});
});
});
</script>
