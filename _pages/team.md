---
title: "Allan Lab - Team"
layout: gridlay
excerpt: "Allan Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


Jump to [Master students](#master), [Bachelor students](#bachelor), [Lab visitors](#lab-visitors), [Alumni](#alumni).

## Principle Investigator    
  
![]({{ site.url }}{{ site.baseurl }}/images/profile.jpg){: style="width: 140px; float: left; margin: 15px 30px 15px 0px;"} 

<br/>
#### Jingwen Yan, Ph.D
*Assistant Professor, Bioinformatics*     
*IUPUI*     


Email: jingyan@iu.edu    
Office: IT 481   
Phone (Office): (317) 278-7668  

<br/>
## PhD Students
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
