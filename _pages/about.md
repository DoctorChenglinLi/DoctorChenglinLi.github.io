---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

<style>
p.txt {
  text-align: justify;
}
</style>

## About 

{% for member in site.data.pi %}
<div class="jumbotron">
<div class="row">
<div class="col-sm-4">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" width="100%" style="max-width:250px"/>
</div>
<div class="col-sm-8 col-xs-12">
  <h3>{{ member.name }}</h3>
  <h4><i>{{ member.info }}</i></h4>
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}

  <ul style="overflow: hidden">
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education5 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 6 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education5 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education6 | replace: "-","&#8211;"}} </li>
  {% endif %}
  </ul>
</div>
</div>
</div>
{% endfor %}

<!--
{% if site.data.grants %}
<div class="jumbotron">
  <h4>Grants</h4>
<ul>
{% for grant in site.data.grants %}
 <li> {{ grant.name }} </li>
{% endfor %}
</ul>
</div>
{% endif %}
-->

  <h4>Awards</h4>
<ul>
  <li><p class="txt">(2017) Second Place (CUHK team) of the 4th Student Challenge in the 32nd Annual Meeting of the American Society for Precision Engineering (ASPE 2017)
  [@Award](/awards/ASPE 2017.pdf){:target="_blank"} </p></li>
  <li><p class="txt">(2016) Second Prize of Life Sciences Group in the 2nd Hong Kong University Student Innovation and Entrepreneurship Competition
  [@Award](/awards/HK 2016.pdf){:target="_blank"} </p></li>
  <li><p class="txt">(2015) Merit Award of Mechanics & Control Systems Group in the 1st Hong Kong University Student Innovation and Entrepreneurship Competition </p></li>
  <li><p class="txt">(2015) Postgraduate Individual Merit of Professor Charles K. Kao Student Creativity Awards
  [@Award](/awards/PCKKSCA 2015.pdf){:target="_blank"} </p></li>
  <li><p class="txt">(2012) Best System Control Award and Excellent Team Culture Award (THU team) in International Aerial Robotic Competition (IARC 2012)
  [@Award](/awards/IARC6.pdf){:target="_blank"} </p></li>
  
<p class="txt">S. Chen, <u>C. Li</u>, and J. Wang, "Method and Apparatus for Dynamic Tuning", *U.S. Patent*, No. 9,527,733, Dec 27th, 2016.
[@Patent](https://patents.google.com/patent/US9527733B2/en){:target="_blank"}</p>
</ul>


<!--
{% if site.data.people %}
<div class="jumbotron">
  <h4>Students and mentoring</h4>
<ul>
{% for student in site.data.people %}
 <li> {{ student.name }}, {{student.location}} ({{student.degree}}, {{student.year}}) </li>
{% endfor %}
</ul>
</div>
{% endif %}
-->

<!--
{% if site.data.funders %}
<div class="jumbotron">
  <h4>Sponsors</h4>
  <div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
  {% for funder in site.data.funders %}<a href="{{ funder.url }}" target="_blank"><img src='{{ site.url }}{{ site.baseurl }}/images/{{ funder.image }}' style='max-height: 80px; max-width: 200px; margin: 1%'/></a>{% endfor %}
  </div>
</div>
{% endif %}
-->
