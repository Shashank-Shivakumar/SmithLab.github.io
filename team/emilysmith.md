---
layout: homelay
title: Emily R. Smith
position: Principal Investigator
handle: emilysmith
email: 
twitter: DrEmilyRSmith
github: emily-r-smith
scholar: qQx4iIwAAAAJ
photo: emilysmith.jpg
gwu: emily-smith
linkedin: 
---
{% assign member = page %}

<div class="container-fluid our-team">
<section class="container">
<div class="col-lg-3 col-mg-3 col-sm-12 col-xs-12 col-lg-offset-1">
<div class="profile-img">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" width="400" height="400" alt="{{ member.title }}">
</div>				
</div>
<div class="col-lg-7 col-mg-7 col-sm-12 col-xs-12 col-lg-offset-1">
<div class="profile-info">
<h1>{{ member.title }}</h1>
<h4>{{ member.position }}</h4>
<div class="bx social-icons">
<span class="w-txt">Follow me on</span>
{{ member.email | prepend: 'mailto:' | prepend: '<a href="' | append: '"><i class="fa fa-inbox fa-fw" aria-hidden="true"></i></a>' if member.email }}
{{ member.gwu | prepend: 'https://publichealth.gwu.edu/departments/global-health-exercise-and-nutrition-sciences/' | prepend: '<a href="' | append: '"><i class="fa fa-university" aria-hidden="true"></i></a>' if member.gwu }}
{{ member.twitter | prepend: 'https://twitter.com/' | prepend: '<a href="' | append: '"><i class="fa fa-twitter-square" aria-hidden="true"></i></a>' if member.twitter }}
{{ member.github | prepend: 'https://github.com/' | prepend: '<a href="' | append: '"><i class="fa fa-github-square" aria-hidden="true"></i></a>' if member.github }}
{{ member.scholar | prepend: 'http://scholar.google.com/citations?user=' | prepend: '<a href="' | append: '"><i class="ai ai-google-scholar-square ai-1x" aria-hidden="true"></i></a>' if member.scholar }}
{{ member.linkedin | prepend: 'https://www.linkedin.com/in/' | prepend: '<a href="' | append: '"><i class="fa fa-linkedin" aria-hidden="true"></i></a>' if member.linkedin }}
{{ member.researchGate | prepend: 'https://www.researchgate.net/profile/' | prepend: '<a href="' | append: '"><i class="fa fa-graduation-cap" aria-hidden="true"></i></a>' if member.researchGate }}
{{ member.orcid | prepend: 'https://orcid.org/' | prepend: '<a href="' | append: '"><i class="fab fa-orcid" aria-hidden="true"></i></a>' if member.orcid }}
</div>
</div>
</div>
</section>
</div>	


<section class="container">
<div class="col-lg-8 col-md-8 col-sm-12 col-xs-12 col-lg-2-offset col-md-offset-2">
<h4>Overview</h4>
<p>Dr. Smith is an assistant professor at school of public health in GWU. Her research focuses on infection and nutrition across the life course, with a goal of generating, analyzing, and translating epidemiological data to improve maternal, newborn, and child health in low- and middle-income countries. She has worked on the design, implementation, and analysis of randomized trials, surveillance, and health service program evaluations in Tanzania, Ghana, Bolivia, Peru, Rwanda, Uganda, Afghanistan, and the U.S. to evaluate the efficacy and effectiveness of health interventions. She has worked closely with WHO to synthesize and translate evidence for use in global policy contexts on topics including: risk of SARS-CoV-2 in pregnancy; mother-to-child transmission of SARS-CoV-2; efficacy and safety of neonatal vitamin A supplementation, and interventions for care and feeding of low birthweight infants. As an epidemiologist, my technical expertise includes study design and data analysis for randomized trials, surveillance, and conducting meta-analyses.</p>
<div class="bx space4">&nbsp;
</div>
<h4>Education</h4>
<ul>
<li>PhD, Harvard T.H Chan School of Public Health, MA</li>
<li>MPH, Emory University, GA</li>
<li>BA, Northwestern University, IL</li>
</ul>
</div>
</section>
