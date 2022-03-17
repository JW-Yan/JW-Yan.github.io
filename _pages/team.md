---
title: "Jingwen Lab - Team"
layout: gridlay
excerpt: "Jingwen Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students and Postdocs to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


Jump to [Master students](#master), [Bachelor students](#bachelor), [Lab visitors](#lab-visitors), [Alumni](#alumni).

## Principle Investigator  
![]({{ site.url }}{{ site.baseurl }}/images/profile.jpg){: style="width: 130px; float: left; margin: 30px 30px 50px 10px;"}
#### Jingwen Yan, Ph.D
*Assistant Professor, Bioinformatics*   
📧 [jingyan@iu.edu](mailto:jingyan@iu.edu)<br/>   

Dr. Jingwen Yan is an Assistant Professor of Bioinformatics in the [Department of BioHealth Informatics](https://soic.iupui.edu/biohealth/) at Indiana University   Purdue University Indianapolis (IUPUI). She obtained her Ph.D. degree in Bioinformatics from Indiana University. Her research interests include bioinformatics, biomedical informatics, machine learning, network science, brain imaging genomics, multi-omics and systems biology, and the applications in Alzheimer’s and other complex diseases. 

## PhD Students
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

<div class="row">

<div class="col-sm-12 clearfix">
  <div class="col-sm-2">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="100%" style="float: left" />
  </div>
  <div class="col-sm-10">
  <h4>{{ member.name }}</h4>
  <i> {{member.info}} </i> <br/>
  📧 [{{member.email}}](mailto:{{member.email}}) <br/>
  
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  </ul>
    
    *Research interest:* {{member.research_interest}}
  </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

</div>

{% endfor %}


## Master Students<a name="master"></a>
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

<div class="row">

<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>1. xxxxxxxxxxxxxxx. xxx xxx xx xx xxx xx xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx. xxx xxxxxxx xxxxxxxxxxxxxxxxxxxxxxxxx xxxxxxxxxxxxx xxxx <!--<br>email: <{{ member.email }}></i> -->
  <i>2. xxxxxxxxxxxxxxxxxxxxxxxxxx
</div>

{% assign number_printed = number_printed | plus: 1 %}

</div>

{% endfor %}

## Bachelor Students<a name="bachelor"></a>
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

<div class="row">

<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>1. xxxxxxxxxxxxxxx. xxx xxx xx xx xxx xx xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx. xxx xxxxxxx xxxxxxxxxxxxxxxxxxxxxxxxx xxxxxxxxxxxxx xxxx <!--<br>email: <{{ member.email }}></i> -->
  <i>2. xxxxxxxxxxxxxxxxxxxxxxxxxx
</div>

{% assign number_printed = number_printed | plus: 1 %}

</div>

{% endfor %}


## Lab Visitors<a name="lab-visitors"></a>

<div class="row">
<div class="col-sm-12 clearfix">
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>
</div>

## Alumni<a name="alumni"></a>

<div class="row">
<div class="col-sm-12 clearfix">
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>
</div>
