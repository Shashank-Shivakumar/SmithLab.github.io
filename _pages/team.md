---
title: "Smith Lab - Team"
layout: default
excerpt: "Smith Lab: Team members"
sitemap: false
permalink: /team/
---
<!--<html>
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
<!--Leadership section ends-->			

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
{% endif %}
</body>
</html>
-->

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<title>Smith Lab - Our Team</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap" rel="stylesheet">
<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="css/smithlab.css">
</head>
<body>

<header class="navbar" role="navigation">
<div class="container">
<div class="navbar-header s-lab-header">
<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse-1" aria-expanded="false">
<span class="sr-only">Toggle navigation</span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
</button>

<a class="navbar-brand" href="/SmithLab.github.io/">Smith Lab | GW School of Public Health</a>
</div>

<div class="collapse navbar-collapse" id="navbar-collapse-1">
<ul class="nav navbar-nav navbar-right">
<li><a href="/SmithLab.github.io/">Home</a></li>
<li><a href="/SmithLab.github.io/team" class="active">Our Team</a></li>
<li><a href="/SmithLab.github.io/research">Research</a></li>
<li><a href="/SmithLab.github.io/publications">Publications</a></li>
<li><a href="/SmithLab.github.io/funders_partners">Get in Touch</a></li>
<li><a href="/SmithLab.github.io/recruitment">Join Us</a></li>
<li><a href="/SmithLab.github.io/code"><i class="fa fa-github" style="font-size:24px"></i></a></li>

<!-- <li><a href="/SmithLab.github.io/data">Data</a></li> -->
<!-- <li><a href="/SmithLab.github.io/contact">Contact</a></li> -->
</ul>
</div>
</div>
</header>


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

<div class="container-fluid">		
<!--publication section starts here-->
<section class="container">
<div class="bx section-title-area">
<h2 class="section-title">Leadership</h2>
</div>
<div class="bx leadership-team">
<div class="bx team-main-bx">
<div class="media">
<img src="images/teampic/emilysmith.jpg" width="480" height="480" alt="Emily R Smith">
</div>
<div class="info">
<h4>Emily R. Smith</h4>
<h5>Associate Professor</h5>
</div>
</div>

<div class="bx team-main-bx">
<div class="media">
<img src="images/teampic/fouziafarooq.jpg" width="480" height="480" alt="Fouzia Farooq">
</div>
<div class="info">
<h4>Fouzia Farooq</h4>
<h5>Associate Professor</h5>
</div>
</div>
</div>
</section>
<!--publication section ends-->					
</div>

<section class="container">
<div class="bx section-title-area">
<h2 class="section-title">Trainees</h2>
</div>
<div class="bx recent-updates">
<div class="bx trainee">
<div class="media">
<img src="images/teampic/wenchienyang.jpg" width="320" height="320" alt="Wen-chien Yang">
</div>
<div class="info">
<h4>Wen-chien Yang</h4>
<h5>PhD Student</h5>
</div>
</div>

<div class="bx trainee">
<div class="media">
<img src="images/teampic/ramaachitale.jpg" width="320" height="320" alt="Ramaa Chitale">
</div>
<div class="info">
<h4>Ramaa Chitale</h4>
<h5>DrPH Student</h5>
</div>
</div>

<div class="bx trainee">
<div class="media">
<img src="images/teampic/megantalej.jpg" width="320" height="320" alt="Megan Talej">
</div>
<div class="info">
<h4>Megan Talej</h4>
<h5>PhD Student</h5>
</div>
</div>

<div class="bx trainee">
<div class="media">
<img src="images/teampic/jennykim.jpg" width="320" height="320" alt="Jenny Kim">
</div>
<div class="info">
<h4>Jenny Kim</h4>
<h5>PhD Student</h5>
</div>
</div>
<div class="bx trainee">
<div class="media">
<img src="images/teampic/xinyili.jpg" width="320" height="320" alt="Xinyi Li">
</div>
<div class="info">
<h4>Xinyi Li</h4>
<h5>PhD Student</h5>
</div>
</div>
</div>
</section>

<section class="container">
<div class="bx section-title-area">
<h2 class="section-title">Research Staff</h2>
</div>
<div class="bx recent-updates">
<div class="bx trainee">
<div class="media">
<img src="images/teampic/xiaoyan-hu.jpg" width="320" height="320" alt="Xiaoyan Hu">
</div>
<div class="info">
<h4>Xiaoyan Hu</h4>
<h5>Senior Research Associate, Data Management</h5>
</div>
</div>

<div class="bx trainee">
<div class="media">
<img src="images/teampic/stacie-loisate.jpg" width="320" height="320" alt="Stacie Loisate">
</div>
<div class="info">
<h4>Stacie Loisate</h4>
<h5>Senior Research Associate,<br>Data Management</h5>
</div>
</div>

<div class="bx trainee">
<div class="media">
<img src="images/teampic/victoria-reynolds.jpg" width="320" height="320" alt="Victoria Reynolds">
</div>
<div class="info">
<h4>Victoria Reynolds</h4>
<h5>Senior Research Associate</h5>
</div>
</div>

<div class="bx trainee">
<div class="media">
<img src="images/teampic/erinoakley.jpg" width="320" height="320" alt="Erin Oakley">
</div>
<div class="info">
<h4>Erin Oakley</h4>
<h5>Senior Research Associate</h5>
</div>
</div>
<div class="bx trainee">
<div class="media">
<img src="images/teampic/sasha-baumann.jpg" width="320" height="320" alt="Sasha Baumann">
</div>
<div class="info">
<h4>Sasha Baumann</h4>
<h5>Senior Research Associate</h5>
</div>
</div>
<div class="bx trainee">
<div class="media">
<img src="images/teampic/jaimemarquis.jpg" width="320" height="320" alt="Jaime Marquis">
</div>
<div class="info">
<h4>Jaime Marquis</h4>
<h5>Research Associate</h5>
</div>
</div>
<div class="bx trainee">
<div class="media">
<img src="images/teampic/molayoifebajo.jpg" width="320" height="320" alt="Molayo Ifebajo">
</div>
<div class="info">
<h4>Molayo Ifebajo</h4>
<h5>Research Assistant</h5>
</div>
</div>
<div class="bx trainee">
<div class="media">
<img src="images/teampic/preciouswilliams.jpg" width="320" height="320" alt="Precious Williams">
</div>
<div class="info">
<h4>Precious Williams</h4>
<h5>Research Assistant</h5>
</div>
</div>
</div>
</section>

<section class="container">
<div class="bx section-title-area">
<h2 class="section-title">Alumni</h2>
</div>
<div class="bx recent-updates">
<div class="bx alumni">
<h4>Clara Parsons</h4>
<h5>Senior Research Assistant (2022)</h5>
</div>
<div class="bx alumni">
<h4>Eliza Fishman, MPH</h4>
<h5>MPH Student (2023)</h5>
</div>
<div class="bx alumni">
<h4>Siran He, PhD</h4>
<h5>Postdoctoral Scholar (2020-2021)<br>
Current: Centers for Disease Control and Prevention</h5>
</div>
<div class="bx alumni">
<h4>Xiang Li, PhD</h4>
<h5>Senior Research Assistant (2021-2022)<br>
Current: Capital One </h5>
</div>
<div class="bx alumni">
<h4>Gargi Wable Grandner, PhD</h4>
<h5>Postdoctoral Scholar (2021-2022)<br>
Current: ACDI/VOCA</h5>
</div>
<div class="bx alumni">
<h4>Dina Moradian, MPH</h4>
<h5>MPH Student (2020-2022)<br>
Current: Children’s National Hospital</h5>
</div>
<div class="bx alumni">
<h4>Allison Schwedock, MPH</h4>
<h5>MPH Student (2022)<br>
Current: GW Milken Institute School of Public Health</h5>
</div>
<div class="bx alumni">
<h4>Alexandra Bellows, PhD</h4>
<h5>Senior Research Associate (2021-2022)<br>
Current: The University of Edinburgh</h5>
</div>
<div class="bx alumni">
<h4>Jamie Thivener</h4>
<h5>MPH Student (2022)<br>
Current: John Snow, Inc (JSI)</h5>
</div>
<div class="bx alumni">
<h4>Kacey Ferguson</h4>
<h5>Research Assistant (2021-2022)<br>
Current: NYU Grossman School of Medicine</h5>
</div>
<div class="bx alumni">
<h4>Rebecca Zavala</h4>
<h5>Project Manager (2021)<br>
Current: Child and Adolescent Health Measurement Initiative (CAHMI) at JHSPH</h5>
</div>
<div class="bx alumni">
<h4>Alexandra Fogel</h4>
<h5>Research Assistant (2020-2021)<br>
Current: Harvard University</h5>
</div>
<div class="bx alumni">
<h4>Jamie Minchin, MPH</h4>
<h5>MPH Student (2020-2021)<br>
Current: Office of Country Support, Bureau of Global Health, USAID</h5>
</div>
<div class="bx alumni">
<h4>Janay Johnson, MPH</h4>
<h5>Research Assistant (2020-2021)<br>
Current: University of Maryland School of Public Health</h5>
</div>
<div class="bx alumni">
<h4>Padmini Kucherlapaty, MsC, MPH</h4>
<h5>Research Assistant (2020-2021)<br>
Current: Truth Initiative</h5>
</div>
<div class="bx alumni">
<h4>Chioniso Jakazi, MPH</h4>
<h5>Research Assistant (2019-2021)<br>
Current: Howard University Hospital</h5>
</div>
</div>
</section>

<footer class="bx footer">
<div class="container">
<div class="bx txt-a-c cta-wrapper line-cta">
<a href="#" class="btn btn-primary footer-nav">Join Our Group</a>
<a href="#" class="btn btn-primary footer-nav">Our Sponsers</a>
<a href="#" class="btn btn-primary footer-nav">Get in Touch</a>
</div>
</div>
</footer>


<script type="text/javascript" src="js/jquery-3.7.1.min.js"></script>
<script type="text/javascript" src="js/bootstrap.min.js"></script>
</body>
</html>
