---
title: "Smith Lab - Team"
layout: default
excerpt: "Smith Lab: Team members"
sitemap: false
permalink: /team/
---
<html>
<body>
<div class="container-fluid our-team">
<section class="container">
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 x-p">
<h1 class="w-txt">Our Team</h1>
<p class="a7-w-txt">Short description about the research team goes here and here also, short description about the research team goes here and here also.</p>
</div>
<div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">

</div>
</section>
</div>

Leadership section starts here
<div class="container-fluid">		
<section class="container">
<div class="bx section-title-area">
<h2 class="section-title">Leadership</h2>
</div>

<div class="bx leadership-team">

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if member.group == 0 %}

{% if even_odd == 0 %}
<div class="bx team-main-bx">
{% endif %}

<div class="media">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/teampic/{{ member.photo }}" width="480" height="480" alt="{{ member.name }}">
</div>
<div class="info">
<h4>{{ member.name }}</h4>
<h5>{{ member.info }}</h5>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

</section>
</div>
</body>
</html>
<!-- Leadership section ends

<!-- {% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if member.group == 0 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/teampic/{{ member.photo }}" class="img-responsive" width="40%" style="float: left; border-radus: 50%" />
  <h4><a href="{{ member.url }}" class="off">{{ member.name }}</a></h4>
  <i>{{ member.info }}</i>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %} -->